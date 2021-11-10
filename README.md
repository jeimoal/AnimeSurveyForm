# AnimeSurveyForm
Desenvolvimento de formulário para certificação do site FreeCodeCamp

HTML pronto!<br>
CSS em desenvolvimento.<br>
<br>
<DOCTYPE! html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <link href="_css/style.css" type="text/css" rel="stylesheet">
    </head>
    <body>
        <header>
            <h1 id="title">Anime Survey Form</h1>
            <p id="description">Thank you for taking your time to respond</p>
        </header>
        <form id="survey-form">
            <span id="data-group">
                <div>
                    <label id="name-label" for="name">Name</label>
                    <input
                        type="text"
                        name="name"
                        id="name"
                        placeholder="*Your real name, please!"
                        required
                    >
                </div>
                <div>
                    <label id="number-label" for="number">Age</label>
                    <input
                        type="number"
                        name="number"
                        id="number"
                        min="10"
                        max="90"
                        placeholder="*Enter your real age"
                        required
                    >
                </div>
                <div>
                    <label id="email-label" for="email">E-mail</label>
                    <input
                        type="email"
                        name="email"
                        id="email"
                        min="8"
                        max="90"
                        placeholder="*Enter your best email"
                        required
                    >
                </div>
            </span>
            <div>
                <p>Wich kind of protagonist do you prefer?</p>
                <select id="dropdown" name="protagonist" required>
                    <option disabled selected value>Select your protagonist</option>
                    <option value="Haremking">Generic Harem king</option>
                    <option value="tsu-yan">Tsundere / Yandere</option>
                    <option value="oujou">Oujou-sama</option>
                    <option value="Overpower">Overpower</option>
                    <option value="Undeserved">Undeserved</option>
                </select>
            </div>
            <div id="radio-group">
                <p>Which Anime Style do you like? (Check all you like)</p>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="harem"
                        value="Harem"
                    >Harem
                </label>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="ecchi"
                        value="ecchi"
                    >Ecchi
                </label>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="isekai"
                        value="isekai"
                    >Isekai
                </label>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="shonen"
                        value="shonen"
                    >Shonen
                </label>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="shoujo"
                        value="shoujo"
                    >Shoujo
                </label>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="seinen"
                        value="seinen"
                    >Seinen
                </label>
                <label>
                    <input
                        type="checkbox"
                        name="animestyle"
                        id="hentai"
                        value="hentai"
                    >Hentai
                </label>
            </div>
            <div>
                <p>How many hours do you spend daily watching Anime?</p>
                <label>
                    <input                        
                        name="hours"                        
                        value="1hour"
                        type="radio"
                    >1 hour
                </label>
                <label>
                    <input                        
                        name="hours"                        
                        value="2hour"
                        type="radio"
                    >   2 hours
                </label>
                <label>
                    <input                        
                        name="hours"                        
                        value="3hour"
                        type="radio"
                    >3 hours
                </label>
                <label>
                    <input                        
                        name="hours"                        
                        value="4hour"
                        type="radio"
                    >4 hours
                </label>
                <label>
                    <input                        
                        name="hours"                        
                        value="5hour"
                        type="radio"
                    >5+ hours!
                </label>
            </div>
            <div>
                <p>Any comments or suggestions?</p>
                <textarea
                id="comments"
                name="comments"
                placeholder="Any comments or suggestions?"></textarea>
            </div>
            <div>
                <button
                type="submit"
                id="submit"
                >Submit
                </button>
            </div>
        </form>
    </body>
</html>

