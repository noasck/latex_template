# latex_template
Template for general-purpose latex files
# Snippets

'.tex':
  'limit':
    'prefix': 'lim'
    'body': ' \\\\lim\\\\limits_{$1\\\\to ${2: \\\\infty}}{$3} = $4'
  'summ':
    'prefix': 'sum'
    'body': ' \\\\sum\\\\limits_{$1 = $2}^{${3: \\\\infty}}{$4}'
  'Integr a_b':
    'prefix': 'int'
    'body': ' \\\\int\\\\limits_{$1}^{${2: +\\\\infty}}{$3}'
  'limit_to_o':
    'prefix': 'lim0'
    'body': ' \\\\lim\\\\limits_{$1\\\\to0}{$2} $3'
  'fraction':
    'prefix': '\/'
    'body': '\\\\frac{$1}{$2} $3'
  'epsilon':
    'prefix': 'eps'
    'body': '\\\\varepsilon $1'
  'module':
    'prefix': '\|'
    'body': '\\\\left\\\| $1 \\\\right\\\| $2'
  'big_round_bracket':
    'prefix': 'bir'
    'body': '\\\\left\\\( $1 \\\\right\\\) $2'
  'braket':
    'prefix': 'braket'
    'body': '\\\\left\\\\lbrace $1 \\\\right\\\\rbrace $2'
  'neq':
    'prefix': '\!\='
    'body': '\\\\neq '
  'geq':
    'prefix': '\>\='
    'body': '\\\\geq '
  'leq':
    'prefix': '\<\='
    'body': '\\\\leq '
  'proof':
    'prefix': 'proof'
    'body': '\\\\begin\\\{proof\\\}\n $1 \n\\\\end\\\{proof\\\}'
  'theorem':
    'prefix': 'bteo'
    'body': '\\\\begin\\\{boxteo\\\}\n $1 \n\\\\end\\\{boxteo\\\}'
  'gathered':
    'prefix': 'gathered'
    'body': '\\\\begin\\\{gathered\\\}\n $1 \n\\\\end\\\{gathered\\\}'
  'bmatrix':
    'prefix': 'bmatrix'
    'body': '\\\\begin\\\{bmatrix\\\}\n $1 \n\\\\end\\\{bmatrix\\\}'
  'alpha':
    'prefix': 'alp'
    'body': '\\\\alpha'
  'rational':
    'prefix': 'R',
    'body': '\\\\mathbb\\\{R\\\}'
  'overline':
    'prefix': '\_\_',
    'body': '\\\\overline\\\{$1\\\}'
  'sin':
    'prefix': 'sin'
    'body': '\\\\sin\\\{\\\($1\\\)\\\} '
  'cos':
    'prefix': 'cos'
    'body': '\\\\cos\\\{\\\($1\\\)\\\} '
  'tg':
    'prefix': 'tg'
    'body': '\\\\tg\\\{\\\($1\\\)\\\} '
  'varphi':
    'prefix': 'fi'
    'body': '\\\\varphi'
  'omega':
    'prefix': 'w'
    'body': '\\\\omega'
  'theta':
    'prefix': 't'
    'body': '\\\\theta'
  'includegraphics':
    'prefix': 'image'
    'body': '\\\\begin{center} \\\\includegraphics\\\[scale=$1\\\]\\\{$2\\\} \\\\end\\\{center\\\}'
