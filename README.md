<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
        }

        table {
            width: 800px;
            border-collapse: collapse;
            position: relative;
        }

        td,
        th {
            border: 1px solid black;
            padding: 8px;
        }

        thead,
        tfoot {
            background-color: gray;
            color: white;
        }

        thead>tr>th {
            position: sticky;
            top: 0;
            background-color: gray;

        }

        td.num {
            text-align: right;
        }

        caption {
            font-size: 1.5em;
            font-weight: bold;
            padding: 10px;
            background-color: lightgray;
        }
    </style>
</head>

<body>
    <h1>Uso de tabelas grandes</h1>

    <table>
        <caption>
            População das Unidades Federativas
        </caption>
        <thead>
            <tr>

                <th scope="col">Estado</th>
                <th scope="col" style="width: 100px">População</th>
                <th> Comando HTML ultilizado </th>
            </tr>

        </thead>
        <tbody>
            <tr>
                <td>Acre</td>
                <td class="num"> <mark> 830.018 </mark></td>
                <td><b>'Negrito'e <mark> 'Destacado' </mark></b></td>
            </tr>
            <tr>
                <td>Alagoas</td>
                <td class="num">3.365.351</td>
                <td><i> 'Itálico' </i></td>
            </tr>
            <tr>
                <td><u>Amapá</u></td>
                <td class="num">877.613</td>
                <td><u>'Texto sublinhado'</u></td>
            </tr>
            <tr>
                <td><del>Amazonas</del></td>
                <td class="num"><u>4.269.995</u></td>
                <td><del>'Texto Marcado'</del> e <u>'Texto Sublinhado'</u></td>
            </tr>
            <tr>
                <td><sub>Bahia</sub></td>
                <td class="num">14.141.626</td>
                <td><sub>'Texto Subrescrito'</sub></td>
            </tr>
            <tr>
                <td><abbr title="Ceara">Ce</abbr>
                </td>
                <td class="num">9.240.580</td>
                <td>'Abreviação'</td>
            </tr>
            <td> <strong> Distrito Federal </strong></td>
            <td class="num">3.098.883</td>
            <td> <strong>'Texto em negrito'</strong> </td>
            <tr>
                <td><q>Espirito Santo</q></td>
                <td class="num">4.108.508</td>
                <td>'<q>Citaçao Curta</q>'</td>
            </tr>
            <tr>
                <td><q>Goias</q></td>
                <td class="num"> 7.206.589</td>
                <td><q>'Citação de fonte'</q></td>
            </tr>
            <tr>
                <td><tt> Maranhão </tt></td>
                <td class="num">6.775.805</td>
                <td><tt>'Texto Monoespaçado'</tt></td>
            </tr>
            <tr>
                <td>
                    <pre>Mato Grosso </pre>
                </td>
                <td class="num">3.683.813</td>
                <td>
                    <pre>'Texto pre-formatado'</pre>
                </td>
            </tr>
            <tr>
                <td><small> Paraiba </small></td>
                <td class="num">4.059.905</td>
                <td><small>'Texto pequeno'</small></td>
            </tr>
            <tr>
                <td><sup>Piaui</sup></td>
                <td class="num">3.281.480</td>
                <td><sup>'Texto Subscrito'</sup></td>
            </tr>
            <tr>
                <td>
                    <blockquote> Rio de janeiro </blockquote>
                </td>
                <td class="num">16.054.524 </td>
                <td>
                    <blockquote>'Citação em blocos'</blockquote>
                </td>
            </tr>
            <tr>
                <td><strong> Rio Grande do Sul </strong></td>
                <td class="num">10.882.965</td>
                <td><strong>'Negrito'</strong></td>
            </tr>
            <tr>
                <td><i> Rondônia </i></td>
                <td class="num">1.616.379</td>
                <td><i>'Itálico'</i></td>
            </tr>
            <tr>
                <td><mark> Roraima </mark></td>
                <td class="num">636.707</td>
                <td><mark>'Texto destacado'</mark></td>
            </tr>
            <tr>
                <td><abbr title="Tocantins">TO</abbr></td>
                <td class="num">1.607.363 </td>
                <td>'Abreviação'</td>

            </tr>


        </tbody>
        <tfoot>
            <tr>
                <td><b> Total da População </b> </td>
                <td> <b> 95.738.023</b></td>
                <td> <b> Realiza as soma da coluna </b> </td>
            </tr>

        </tfoot>

        </head>

        <body>

        </body>

</html>
