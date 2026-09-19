<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#svgIDa)"><path fill="url(#svgIDb)" class="skdh8c8wf"/><path fill="url(#svgIDc)" class="skdh8c8wf"/></g><g filter="url(#svgIDd)"><path fill="url(#svgIDe)" class="b0c6xjbyb"/></g><g filter="url(#svgIDf)"><path class="a9vjn3b8f"/></g><path fill="url(#svgIDg)" class="g1-cakgjb"/><path fill="url(#svgIDh)" class="g1-cakgjb"/><path fill="url(#svgIDi)" class="tjubatb2f"/><path fill="url(#svgIDj)" class="tjubatb2f"/><circle fill="url(#svgIDk)" class="rdymgqtsv"/><g filter="url(#svgIDl)"><path clip-rule="evenodd" class="kkrh02mfv"/></g><circle fill="url(#svgIDm)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDn)"><path clip-rule="evenodd" class="b-pbhbb4p"/></g><path fill="url(#svgIDo)" class="ldd357aax"/><path fill="url(#svgIDp)" class="ldd357aax"/><g filter="url(#svgIDq)"><path class="as84bwsgg"/></g><path class="mngobgbzy"/><path fill="url(#svgIDr)" class="j7sojhblo"/><g filter="url(#svgIDs)"><path class="g6a574b3m"/></g><path fill="url(#svgIDt)" class="nykqrqb8m"/><path fill="url(#svgIDu)" class="nykqrqb8m"/><path fill="url(#svgIDv)" class="nykqrqb8m"/><path fill="url(#svgIDw)" class="nykqrqb8m"/><path fill="url(#svgIDx)" class="nykqrqb8m"/><path fill="url(#svgIDy)" class="jaeg0gihu"/><g filter="url(#svgIDz)"><path class="x77uznh9a"/></g><path fill="url(#svgIDA)" class="syv7enbxw"/><path fill="url(#svgIDB)" class="kgr_pob4m"/><g filter="url(#svgIDC)"><path fill="url(#svgIDD)" class="zjev50bzf"/><path fill="url(#svgIDE)" class="zjev50bzf"/></g><path fill="url(#svgIDF)" class="zjev50bzf"/><path fill="url(#svgIDG)" class="zjev50bzf"/><path fill="url(#svgIDH)" class="zjev50bzf"/><path fill="url(#svgIDI)" class="zjev50bzf"/><path fill="url(#svgIDJ)" class="zjev50bzf"/><path fill="url(#svgIDK)" class="zjev50bzf"/><path fill="url(#svgIDL)" class="zjev50bzf"/><path fill="url(#svgIDM)" class="zjev50bzf"/><g filter="url(#svgIDN)"><path class="vns6nwbag"/></g><g filter="url(#svgIDO)"><path class="qs8js6b0o"/><path fill="url(#svgIDP)" class="r5tyubbzf"/><path fill="url(#svgIDQ)" class="r5tyubbzf"/><path fill="url(#svgIDR)" class="r5tyubbzf"/><path fill="url(#svgIDS)" class="r5tyubbzf"/><path fill="url(#svgIDT)" class="r5tyubbzf"/></g><g filter="url(#svgIDU)"><path stroke="url(#svgIDV)" class="deivktyum"/></g><path fill="url(#svgIDW)" class="t1dkn1b9a"/><g filter="url(#svgIDX)"><path fill="url(#svgIDY)" class="jt2azi31h"/></g><path fill="url(#svgIDZ)" class="jt2azi31h"/><path fill="url(#svgIDaa)" class="jt2azi31h"/><path fill="url(#svgIDab)" class="jt2azi31h"/><g filter="url(#svgIDac)"><path class="a0f1t0brm"/></g><g filter="url(#svgIDad)"><path class="f7peuk9er"/></g><g filter="url(#svgIDae)"><path class="pndrqcxcx"/><path fill="url(#svgIDaf)" class="y1fkzut6k"/><path fill="url(#svgIDag)" class="y1fkzut6k"/></g><g filter="url(#svgIDah)"><path class="yjw08ccab"/><path fill="url(#svgIDai)" class="cmy2ggalg"/><path fill="url(#svgIDaj)" class="cmy2ggalg"/><path fill="url(#svgIDak)" class="cmy2ggalg"/></g><path class="mz2-1bfbk"/><path fill="url(#svgIDal)" class="z1un_4z8x"/><path class="xrds8ebpk"/><g filter="url(#svgIDam)"><path class="vsmo47b5i"/><path fill="url(#svgIDan)" class="moyj76b8y"/></g><g filter="url(#svgIDao)"><path fill="url(#svgIDap)" class="rfl05o_kt"/></g><path class="cthy7pi1t"/><path fill="url(#svgIDaq)" class="lkzijqbiz"/><path class="v_jtpob4z"/><g filter="url(#svgIDar)"><path fill="url(#svgIDas)" class="ocp3d13tt"/></g><g filter="url(#svgIDat)" transform="rotate(-27.914 20.796 7.476)"><ellipse class="meeg_hbnd"/><ellipse fill="url(#svgIDau)" class="fho_gq76c"/></g><path fill="url(#svgIDav)" class="g73bznb1o"/><path fill="url(#svgIDaw)" class="g73bznb1o"/><path fill="url(#svgIDax)" class="g73bznb1o"/><path fill="url(#svgIDay)" class="g73bznb1o"/><path fill="url(#svgIDaz)" class="rei3gtbmc"/><path fill="url(#svgIDaA)" class="rei3gtbmc"/><g filter="url(#svgIDaB)"><path fill="url(#svgIDaC)" class="gqubhub0o"/></g><g filter="url(#svgIDaD)"><path fill="url(#svgIDaE)" class="n_1zi0c8z"/></g><g filter="url(#svgIDaF)"><path class="lzsfi18pr"/></g><g filter="url(#svgIDaG)"><path class="x-wewjb5a"/></g><g filter="url(#svgIDaH)"><path class="gcgsyubis"/></g><g filter="url(#svgIDaI)"><path class="tfw8ds16k"/></g><g filter="url(#svgIDaJ)"><path class="iyrh5w2dl"/></g><g filter="url(#svgIDaK)"><path fill="url(#svgIDaL)" class="ecm9b1coi"/></g><g filter="url(#svgIDaM)"><path fill="url(#svgIDaN)" class="qut0ht_ps"/><path fill="url(#svgIDaO)" class="qut0ht_ps"/></g><g filter="url(#svgIDaP)"><path fill="url(#svgIDaQ)" class="a_yyribev"/></g><g filter="url(#svgIDaR)"><path class="z3fl6nbuc"/></g><path fill="url(#svgIDaS)" class="xbx983bqi"/><path fill="url(#svgIDaT)" class="xbx983bqi"/><path fill="url(#svgIDaU)" class="c65lz4_ey"/><path fill="url(#svgIDaV)" class="c65lz4_ey"/><circle fill="url(#svgIDaW)" class="dhdllmbnv"/><g filter="url(#svgIDaX)"><path clip-rule="evenodd" class="fh4v73byj"/></g><circle fill="url(#svgIDaY)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDaZ)"><path clip-rule="evenodd" class="dr85wo1fe"/></g><path fill="url(#svgIDba)" class="c-ymhfbrh"/><path fill="url(#svgIDbb)" class="c-ymhfbrh"/><g filter="url(#svgIDbc)"><path class="qdtbq7bif"/></g><path class="y_jvuobbm"/><path fill="url(#svgIDbd)" class="qy5kkb6yn"/><g filter="url(#svgIDbe)"><path class="yrn5k97fg"/></g><path fill="url(#svgIDbf)" class="zdbmkmbsu"/><path fill="url(#svgIDbg)" class="zdbmkmbsu"/><path fill="url(#svgIDbh)" class="zdbmkmbsu"/><path fill="url(#svgIDbi)" class="zdbmkmbsu"/><path fill="url(#svgIDbj)" class="zdbmkmbsu"/><path fill="url(#svgIDbk)" class="mh1m83zfh"/><g filter="url(#svgIDbl)"><path class="sbcwsbc2z"/></g><path fill="url(#svgIDbm)" class="toow9ybtl"/><path fill="url(#svgIDbn)" class="ezv1h3qjf"/><g filter="url(#svgIDbo)"><path fill="url(#svgIDbp)" class="a2si8_kwh"/><path fill="url(#svgIDbq)" class="a2si8_kwh"/></g><path fill="url(#svgIDbr)" class="a2si8_kwh"/><path fill="url(#svgIDbs)" class="a2si8_kwh"/><path fill="url(#svgIDbt)" class="a2si8_kwh"/><path fill="url(#svgIDbu)" class="a2si8_kwh"/><path fill="url(#svgIDbv)" class="a2si8_kwh"/><path fill="url(#svgIDbw)" class="a2si8_kwh"/><path fill="url(#svgIDbx)" class="a2si8_kwh"/><path fill="url(#svgIDby)" class="a2si8_kwh"/><g filter="url(#svgIDbz)"><path class="t_og1nq1i"/></g><g filter="url(#svgIDbA)"><path class="dx9neboqt"/><path fill="url(#svgIDbB)" class="hkqzqkyse"/><path fill="url(#svgIDbC)" class="hkqzqkyse"/><path fill="url(#svgIDbD)" class="hkqzqkyse"/><path fill="url(#svgIDbE)" class="hkqzqkyse"/><path fill="url(#svgIDbF)" class="hkqzqkyse"/></g><g filter="url(#svgIDbG)"><path stroke="url(#svgIDbH)" class="rh00e0bdu"/></g><path fill="url(#svgIDbI)" class="f21mo8e-f"/><g filter="url(#svgIDbJ)"><path fill="url(#svgIDbK)" class="zanlt2b3w"/></g><path fill="url(#svgIDbL)" class="zanlt2b3w"/><path fill="url(#svgIDbM)" class="zanlt2b3w"/><path fill="url(#svgIDbN)" class="zanlt2b3w"/><g filter="url(#svgIDbO)"><path class="d8iy8ubau"/></g><g filter="url(#svgIDbP)"><path class="ygpxv2fle"/></g><g filter="url(#svgIDbQ)"><path class="lifjftbex"/><path fill="url(#svgIDbR)" class="b7eiottje"/><path fill="url(#svgIDbS)" class="b7eiottje"/></g><g filter="url(#svgIDbT)"><path class="sp4hzm5xt"/><path fill="url(#svgIDbU)" class="x4l_iofys"/><path fill="url(#svgIDbV)" class="x4l_iofys"/><path fill="url(#svgIDbW)" class="x4l_iofys"/></g><path class="gx903pbvq"/><path fill="url(#svgIDbX)" class="n1gy1w_fx"/><path class="i5ql9gb3i"/><g filter="url(#svgIDbY)"><path class="lcsq8judr"/><path fill="url(#svgIDbZ)" class="rx79cpb0u"/></g><g filter="url(#svgIDca)"><path fill="url(#svgIDcb)" class="xbp56ebtm"/></g><path class="s82a0vb9b"/><path fill="url(#svgIDcc)" class="zmosh3beg"/><path class="z264cr8wh"/><g filter="url(#svgIDcd)"><path fill="url(#svgIDce)" class="bzuvwwb_k"/></g><g filter="url(#svgIDcf)" transform="rotate(-27.914 7.75 7.476)"><ellipse class="v145rzbrq"/><ellipse fill="url(#svgIDcg)" class="gj2080cxh"/></g><path fill="url(#svgIDch)" class="x_q13sb6n"/><path fill="url(#svgIDci)" class="x_q13sb6n"/><path fill="url(#svgIDcj)" class="x_q13sb6n"/><path fill="url(#svgIDck)" class="x_q13sb6n"/><path fill="url(#svgIDcl)" class="z44b3ob9l"/><path fill="url(#svgIDcm)" class="z44b3ob9l"/><g filter="url(#svgIDcn)"><path fill="url(#svgIDco)" class="bk817acpw"/></g><g filter="url(#svgIDcp)"><path fill="url(#svgIDcq)" class="ma0zw7mze"/></g><g filter="url(#svgIDcr)"><path class="o7pqjkb6j"/></g><g filter="url(#svgIDcs)"><path class="h7ce0kfzr"/></g><g filter="url(#svgIDct)"><path class="s5fqzlkek"/></g><g filter="url(#svgIDcu)"><path class="e-c-ph2vh"/></g><g filter="url(#svgIDcv)"><path class="ui16d5_tg"/></g><g filter="url(#svgIDcw)"><path fill="url(#svgIDcx)" class="h7h8n338b"/></g><defs><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="cgv9fqb9i"/><stop offset="1" class="e21rj57oo"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.493 3.115) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.284 10.168) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.02 -2.037) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="iohdz6y9b"/><stop offset=".902" class="vvah7_hxr"/></radialGradient><radialGradient id="svgIDA" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 5.98 21.353) scale(.93415 1.1097)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(.64035 .20125 -.62088 1.97552 19.233 8.536)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="svgIDD" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0406 0 0 -3.6098 23.078 7.915)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 9.833 9.338) scale(1.46115 1.2063)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(-.44335 5.38814 -4.46203 -.36714 22.546 5.35)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49805 .61633 0 22.921 7.346)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.4746 .51647 .00186 20.862 7.366)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.68476 .2326 -.59418 -9.4127 23.349 8.343)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="matrix(1.46844 -1.26488 .37362 .43375 18.915 6.73)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="svgIDL" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 9.105 14.37) scale(1.08792 .43489)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37801 -.72568 0 20.899 7.7)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10587 -.33273 0 22.062 8.505)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="svgIDS" cx="0" cy="0" r="1" gradientTransform="matrix(-.73386 .32532 -.52282 -1.17936 22.113 8.258)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(.94634 -.46525 1.8718 3.80736 21.647 9.486)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.18864 -3.1008 4.4 1.68667 19.384 7.08)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.984 -6.11) scale(2.91778 4.1403)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(-.49097 -1.0336 1.22019 -.5796 23.26 5.246)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="matrix(-.95464 0 0 -.3543 21.97 4.796)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="svgIDag" cx="0" cy="0" r="1" gradientTransform="matrix(1.39574 -2.20992 2.44837 1.54634 19.504 6.506)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.52457 -1.2274 1.90221 2.36275 22.692 5.905)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="svgIDaj" cx="0" cy="0" r="1" gradientTransform="matrix(1.28327 -1.14854 2.1027 2.34935 23.002 6.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="svgIDak" cx="0" cy="0" r="1" gradientTransform="matrix(1.39882 .31407 -.1315 .58566 22.628 5.66)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35187 -.5597 0 22.806 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDan" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 13.203 -1.784) scale(.16406 .22589)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3519 -.55972 0 20.914 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21429 .25758 -.00403 20.79 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaw" cx="0" cy="0" r="1" gradientTransform="rotate(74.347 6.97 19.496) scale(1.01039 .96399)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="svgIDax" cx="0" cy="0" r="1" gradientTransform="matrix(.34167 -.46888 .39302 .28638 24.019 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="svgIDay" cx="0" cy="0" r="1" gradientTransform="matrix(.25458 -.67243 .89846 .34016 24.068 7.835)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="matrix(-.7192 0 0 -.80308 19.728 7.802)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(-.39748 .06826 -.06998 -.40753 19.73 7.802)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="cgv9fqb9i"/><stop offset="1" class="e21rj57oo"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.97 7.278) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.762 7.838) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(.45766 -2.68928 1.12443 .19135 8.12 21)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="iohdz6y9b"/><stop offset=".902" class="vvah7_hxr"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.544 11.978) scale(.93415 1.1097)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(.64035 .20125 -.62088 1.97552 6.188 8.536)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0406 0 0 -3.6098 10.032 7.915)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 3.31 5.66) scale(1.46115 1.2063)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(-.44335 5.38814 -4.46203 -.36714 9.5 5.35)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49805 .61633 0 9.876 7.346)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.4746 .51647 .00186 7.818 7.366)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.68476 .2326 -.59418 -9.4127 10.303 8.343)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(1.46843 -1.26489 .37363 .43375 5.869 6.73)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 2.583 8.432) scale(1.08792 .43489)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37801 -.72568 0 7.854 7.7)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10587 -.33273 0 9.017 8.505)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(-.73386 .32532 -.52282 -1.17936 9.067 8.258)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 24.7 -13.753) scale(1.05452 4.2426)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(1.18864 -3.1008 4.4 1.68667 6.34 7.08)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 8.461 -.927) scale(2.91778 4.1403)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 6.766 -.605) scale(1.14428 1.35085)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="svgIDbR" cx="0" cy="0" r="1" gradientTransform="matrix(-.95464 0 0 -.3543 8.924 4.796)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="svgIDbS" cx="0" cy="0" r="1" gradientTransform="matrix(1.39574 -2.20992 2.44837 1.54634 6.46 6.506)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="svgIDbU" cx="0" cy="0" r="1" gradientTransform="matrix(1.52457 -1.2274 1.90221 2.36275 9.647 5.905)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="svgIDbV" cx="0" cy="0" r="1" gradientTransform="matrix(1.28327 -1.14854 2.1027 2.34935 9.957 6.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="svgIDbW" cx="0" cy="0" r="1" gradientTransform="matrix(1.39882 .31407 -.1315 .58566 9.583 5.66)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="svgIDbX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35187 -.5597 0 9.761 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDbZ" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 6.68 1.411) scale(.16406 .22589)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3519 -.55972 0 7.868 7.518)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDcg" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21429 .25758 -.00403 7.744 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDci" cx="0" cy="0" r="1" gradientTransform="rotate(74.347 .448 10.894) scale(1.01039 .96399)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="svgIDcj" cx="0" cy="0" r="1" gradientTransform="matrix(.34167 -.46888 .39302 .28638 10.974 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="svgIDck" cx="0" cy="0" r="1" gradientTransform="matrix(.25458 -.67243 .89846 .34016 11.023 7.835)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="svgIDcm" cx="0" cy="0" r="1" gradientTransform="matrix(-.7192 0 0 -.80308 6.683 7.802)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="svgIDco" cx="0" cy="0" r="1" gradientTransform="matrix(-.39748 .06826 -.06998 -.40753 6.685 7.802)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="svgIDa" width="3.097" height="9.794" x="18.86" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.505882 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDd" width="6.578" height="10.091" x="23.071" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.388235 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDf" width="4.976" height="9.579" x="24.041" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".25"/></filter><filter id="svgIDl" width="5.896" height="7.109" x="15.646" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.388235 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.337255 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDn" width="5.996" height="7.109" x="22.312" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.396078 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.32549 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDq" width="2.703" height="2.68" x="25.244" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".2"/></filter><filter id="svgIDs" width="9.692" height="11.056" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDz" width="2.793" height="3.034" x="16.366" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".2"/></filter><filter id="svgIDC" width="5.433" height="5.453" x="19.664" y="5.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDN" width="2.758" height="3.258" x="20.419" y="6.558" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".5"/></filter><filter id="svgIDO" width=".914" height="1.358" x="21.403" y="7.423" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".025"/></filter><filter id="svgIDU" width="1.746" height=".815" x="20.987" y="8.846" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".05"/></filter><filter id="svgIDX" width="5.583" height="3.907" x="19.068" y="3.578" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDac" width="1.071" height=".63" x="22.549" y="6.204" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDad" width="1.071" height=".623" x="20.269" y="6.211" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDae" width="2.939" height="2.66" x="19.181" y="4.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feGaussianBlur result="effect2_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDah" width="3.621" height="2.884" x="21.82" y="4.163" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feGaussianBlur result="effect2_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDam" width=".455" height=".415" x="22.431" y="7.27" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".05"/></filter><filter id="svgIDao" width=".613" height=".623" x="22.739" y="7.246" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".1"/></filter><filter id="svgIDar" width=".654" height=".678" x="20.812" y="7.219" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".1"/></filter><filter id="svgIDat" width=".509" height=".419" x="20.541" y="7.267" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".05"/></filter><filter id="svgIDaB" width=".859" height="1.315" x="19.081" y="7.145" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".125"/></filter><filter id="svgIDaD" width="1.35" height="1.762" x="23.55" y="6.919" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".25"/></filter><filter id="svgIDaF" width="1.118" height=".578" x="20.197" y="6.319" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDaG" width="1.118" height=".578" x="22.502" y="6.295" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDaH" width="2.177" height="1.171" x="22.376" y="4.8" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".125"/></filter><filter id="svgIDaI" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDaJ" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDaK" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDaM" width="3.097" height="9.794" x="5.815" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.505882 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDaP" width="6.578" height="10.091" x="10.026" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.388235 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDaR" width="4.976" height="9.579" x="10.996" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".25"/></filter><filter id="svgIDaX" width="5.896" height="7.109" x="2.601" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.388235 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.337255 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDaZ" width="5.996" height="7.109" x="9.267" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.396078 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.32549 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDbc" width="2.703" height="2.68" x="12.199" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".2"/></filter><filter id="svgIDbe" width="9.692" height="11.056" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDbl" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".2"/></filter><filter id="svgIDbo" width="5.433" height="5.453" x="6.619" y="5.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDbz" width="2.758" height="3.258" x="7.374" y="6.558" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".5"/></filter><filter id="svgIDbA" width=".914" height="1.358" x="8.357" y="7.423" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".025"/></filter><filter id="svgIDbG" width="1.746" height=".815" x="7.942" y="8.846" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".05"/></filter><filter id="svgIDbJ" width="5.583" height="3.907" x="6.023" y="3.578" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDbO" width="1.071" height=".63" x="9.504" y="6.204" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDbP" width="1.071" height=".623" x="7.224" y="6.211" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/></filter><filter id="svgIDbQ" width="2.939" height="2.66" x="6.136" y="4.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feGaussianBlur result="effect2_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDbT" width="3.621" height="2.884" x="8.775" y="4.163" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feGaussianBlur result="effect2_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDbY" width=".455" height=".415" x="9.386" y="7.27" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".05"/></filter><filter id="svgIDca" width=".613" height=".623" x="9.694" y="7.246" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".1"/></filter><filter id="svgIDcd" width=".654" height=".678" x="7.767" y="7.219" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".1"/></filter><filter id="svgIDcf" width=".509" height=".419" x="7.496" y="7.267" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".05"/></filter><filter id="svgIDcn" width=".859" height="1.315" x="6.036" y="7.145" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".125"/></filter><filter id="svgIDcp" width="1.35" height="1.762" x="10.505" y="6.919" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".25"/></filter><filter id="svgIDcr" width="1.118" height=".578" x="7.152" y="6.319" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDcs" width="1.118" height=".578" x="9.457" y="6.295" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".075"/></filter><filter id="svgIDct" width="2.177" height="1.171" x="9.331" y="4.8" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_712" stdDeviation=".125"/></filter><filter id="svgIDcu" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDcv" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><filter id="svgIDcw" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_712"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_712" result="effect2_innerShadow_4002_712"/></filter><linearGradient id="svgIDb" x1="18.96" x2="20.861" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="yf8e95b_r"/><stop offset="1" class="w9jofw35x"/></linearGradient><linearGradient id="svgIDc" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="rtm0-3azz"/><stop offset="1" class="ds145h5rv"/></linearGradient><linearGradient id="svgIDe" x1="25.173" x2="27.361" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="itvmy4ksx"/><stop offset="1" class="eak9q3b3v"/></linearGradient><linearGradient id="svgIDk" x1="18.017" x2="18.876" y1="16.711" y2="17.376" gradientUnits="userSpaceOnUse"><stop class="c35nx7qyj"/><stop offset="1" class="xh8imlblg"/></linearGradient><linearGradient id="svgIDo" x1="18.383" x2="19.305" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDp" x1="18.899" x2="18.539" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDr" x1="25.133" x2="25.571" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDu" x1="18.774" x2="19.446" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDF" x1="24.096" x2="23" y1="8.646" y2="8.646" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="svgIDP" x1="22.224" x2="21.86" y1="8.208" y2="8.223" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="svgIDR" x1="21.86" x2="21.86" y1="8.702" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="svgIDT" x1="21.86" x2="21.86" y1="7.529" y2="7.766" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="svgIDV" x1="21.338" x2="21.477" y1="9.383" y2="9.021" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="svgIDY" x1="24.832" x2="19.795" y1="5.459" y2="5.459" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="svgIDap" x1="23.143" x2="23.007" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDas" x1="21.236" x2="21.1" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDav" x1="24.651" x2="24.128" y1="7.553" y2="8.497" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="svgIDaz" x1="19.323" x2="19.955" y1="7.858" y2="7.803" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="svgIDaE" x1="24.225" x2="24.225" y1="7.419" y2="8.181" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="svgIDaL" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaN" x1="5.915" x2="7.815" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="yf8e95b_r"/><stop offset="1" class="w9jofw35x"/></linearGradient><linearGradient id="svgIDaO" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="rtm0-3azz"/><stop offset="1" class="ds145h5rv"/></linearGradient><linearGradient id="svgIDaQ" x1="12.128" x2="14.315" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="itvmy4ksx"/><stop offset="1" class="eak9q3b3v"/></linearGradient><linearGradient id="svgIDaW" x1="4.972" x2="5.831" y1="16.711" y2="17.376" gradientUnits="userSpaceOnUse"><stop class="c35nx7qyj"/><stop offset="1" class="xh8imlblg"/></linearGradient><linearGradient id="svgIDba" x1="5.338" x2="6.26" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDbb" x1="5.854" x2="5.495" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDbd" x1="12.088" x2="12.526" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDbg" x1="5.729" x2="6.401" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbr" x1="11.051" x2="9.954" y1="8.646" y2="8.646" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="svgIDbB" x1="9.178" x2="8.815" y1="8.208" y2="8.223" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="svgIDbD" x1="8.815" x2="8.815" y1="8.702" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="svgIDbF" x1="8.815" x2="8.815" y1="7.529" y2="7.766" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="svgIDbH" x1="8.294" x2="8.432" y1="9.383" y2="9.021" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="svgIDbK" x1="11.786" x2="6.75" y1="5.459" y2="5.459" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="svgIDcb" x1="10.098" x2="9.962" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDce" x1="8.191" x2="8.055" y1="7.541" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDch" x1="11.606" x2="11.083" y1="7.553" y2="8.497" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="svgIDcl" x1="6.278" x2="6.91" y1="7.858" y2="7.803" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="svgIDcq" x1="11.18" x2="11.18" y1="7.419" y2="8.181" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="svgIDcx" x1="10.698" x2="7.198" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-bunny-ears-medium" /></template>
<style>
.a_yyribev {
  d: path("m12.729 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-3.465-9.857Z");
}

.a0f1t0brm {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M23.479 6.623a.804.804 0 0 0-.298-.179c-.132-.041-.298-.052-.526-.024a.12.12 0 1 0 .029.238c.209-.025.336-.012.424.016a.56.56 0 0 1 .213.13a.12.12 0 0 0 .158-.181Z");
}

.a2si8_kwh {
  d: path("M6.722 9.114a1.698 1.698 0 0 0 1.685 1.477h.818c.854 0 1.574-.63 1.686-1.477c.05-.817.102-1.63.14-2.447a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465c0 .807.051 1.601.104 2.41Z");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.a9vjn3b8f {
  fill: var(--svg-color--c59b8a, #C59B8A);
  d: path("m24.54 20.164l.824-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.as84bwsgg {
  stroke: var(--svg-color--b68e7e, #B68E7E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.77 12.31l1.083.627c.193.1.578.44.569 1.002");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.b-pbhbb4p {
  fill: var(--svg-color--ac8079, #AC8079);
  fill-rule: evenodd;
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.974-1.72c.93-.82.855-2.148-.348-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.b0c6xjbyb {
  d: path("m25.774 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b7eiottje {
  d: path("M8.915 5.48c-.01-.02-.02-.04-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573c.065-.017.131-.03.196-.041c.467-.076.807.343.807.816v.185l-.009.006Z");
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bk817acpw {
  d: path("M6.609 7.395a.415.415 0 0 0 .036.815a33.847 33.847 0 0 1-.036-.815Z");
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.bzuvwwb_k {
  d: path("M8.221 7.652c0-.125-.102-.208-.13-.233l-.124.12l.077.157l.177-.043Z");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c-ymhfbrh {
  d: path("m5.26 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.814 1.37Z");
}

.c35nx7qyj {
  stop-color: var(--svg-color--8c5a5e, #8C5A5E);
}

.c65lz4_ey {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cgv9fqb9i {
  stop-color: var(--svg-color--a67779, #A67779);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmy2ggalg {
  d: path("m24.12 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.784.22 1.095.422c.756.493.624 1.383.225 1.801Z");
}

.cthy7pi1t {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.823 7.193a.606.606 0 0 0-.588.46a.119.119 0 0 0 .116.147h.968a.1.1 0 0 0 .099-.118a.608.608 0 0 0-.595-.489Z");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d8iy8ubau {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M10.434 6.623a.803.803 0 0 0-.299-.179c-.131-.041-.297-.052-.525-.024a.12.12 0 1 0 .029.238c.208-.025.336-.012.424.016c.086.027.144.07.213.13a.12.12 0 0 0 .158-.181Z");
}

.deivktyum {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M21.86 9.171c-.22 0-.427-.052-.601-.142c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .686-.367c.038-.056-.026-.12-.085-.09c-.174.09-.379.142-.601.142Z");
}

.dhdllmbnv {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
}

.dr85wo1fe {
  fill: var(--svg-color--ac8079, #AC8079);
  fill-rule: evenodd;
  d: path("M9.369 10.716a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.575-2.015a.8.8 0 0 0-1.088.308Z");
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.ds145h5rv {
  stop-color: var(--svg-color--9e7669, #9E7669);
  stop-opacity: 0;
}

.dx9neboqt {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m8.649 7.605l-.23.798c-.048.164.065.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.e-c-ph2vh {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.632-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e21rj57oo {
  stop-color: var(--svg-color--93547f, #93547F);
}

.eak9q3b3v {
  stop-color: var(--svg-color--c09881, #C09881);
}

.ecm9b1coi {
  d: path("M24.093 5.75c.019.097-.102.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.ezv1h3qjf {
  d: path("M6.706 8.457a.711.711 0 0 1-.392-.134v.404c0 .387.23.733.582.876a1.773 1.773 0 0 1-.15-.512l-.04-.634Z");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f21mo8e-f {
  d: path("M8.815 9.171c-.22 0-.427-.052-.601-.142c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .687-.367c.037-.056-.027-.12-.086-.09c-.174.09-.379.142-.601.142Z");
}

.f7peuk9er {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M20.38 6.575a1.203 1.203 0 0 1 .754-.156a.12.12 0 0 1-.029.24a.962.962 0 0 0-.634.144l-.007.005h-.001a.12.12 0 0 1-.147-.19l.064-.043Z");
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fh4v73byj {
  fill: var(--svg-color--9c7765, #9C7765);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.fho_gq76c {
  cx: 20.796px;
  cy: 7.476px;
  rx: 0.169px;
  ry: 0.086px;
}

.ft5dv1b6b {
  fill: none;
}

.g1-cakgjb {
  d: path("m20.928 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g6a574b3m {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.g73bznb1o {
  d: path("M23.994 8.497c.029-.462.056-.923.08-1.385a.698.698 0 0 1-.08 1.385Z");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gcgsyubis {
  fill: var(--svg-color--725050, #725050);
  d: path("M23.767 5.48h-.926a.215.215 0 1 1 .034-.427c.24.038.56.091.774.144c.483.12.617.356.654.524a.674.674 0 0 0-.536-.24Z");
}

.gj2080cxh {
  cx: 7.751px;
  cy: 7.476px;
  rx: 0.169px;
  ry: 0.086px;
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gqubhub0o {
  d: path("M19.654 7.395a.415.415 0 0 0 .036.815a34.16 34.16 0 0 1-.036-.815Z");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gx903pbvq {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.852 7.193c.283 0 .522.195.587.46a.119.119 0 0 1-.116.147h-.967a.1.1 0 0 1-.099-.118a.607.607 0 0 1 .595-.489Z");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h7ce0kfzr {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.375 6.673a1.004 1.004 0 0 0-.718-.166");
}

.h7h8n338b {
  d: path("M11.048 5.75c.019.097-.101.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hkqzqkyse {
  d: path("m8.649 7.605l-.23.798c-.048.164.065.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i5ql9gb3i {
  fill: var(--svg-color--000, #000);
  d: path("M9.54 7.698a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.iohdz6y9b {
  stop-color: var(--svg-color--7b4445, #7B4445);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.itvmy4ksx {
  stop-color: var(--svg-color--9c6b6d, #9C6B6D);
}

.iyrh5w2dl {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.816 3.273c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j7sojhblo {
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jaeg0gihu {
  d: path("m21.662 11.775l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005Z");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jt2azi31h {
  d: path("M23.965 5.034a1.028 1.028 0 0 1 .504 1.552a.676.676 0 0 0-.117.379v.515a.757.757 0 0 0-.29-.116l.034-.697a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.959-.626a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465l.014.667a.741.741 0 0 0-.312.114v-.52a.676.676 0 0 0-.117-.38a1.037 1.037 0 0 1-.063-1.06c.127-.24.332-.407.564-.489c.248-.088.46-.255.6-.481a1.008 1.008 0 0 1 1.254-.396a.646.646 0 0 0 .518 0a1.008 1.008 0 0 1 1.258.41a1.1 1.1 0 0 0 .586.465Z");
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.kgr_pob4m {
  d: path("M19.752 8.457a.712.712 0 0 1-.393-.134v.404c0 .387.23.733.582.876a1.772 1.772 0 0 1-.15-.512l-.04-.634Z");
}

.kkrh02mfv {
  fill: var(--svg-color--9c7765, #9C7765);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.kr_eiac3t {
  r: 0.766px;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lcsq8judr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.733 7.393c.028.037-.03.081-.095.13c-.066.05-.114.084-.142.047c-.028-.037.003-.106.069-.155c.065-.05.14-.06.168-.022Z");
}

.ldd357aax {
  d: path("m18.305 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.813 1.37Z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lifjftbex {
  fill: var(--svg-color--533634, #533634);
  d: path("M8.915 5.48c-.01-.02-.02-.04-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573c.065-.017.131-.03.196-.041c.467-.076.807.343.807.816v.185l-.009.006Z");
}

.lkzijqbiz {
  d: path("M20.913 7.31a.387.387 0 0 0-.373.49h.748a.39.39 0 0 0-.375-.49Z");
}

.lzsfi18pr {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.397 6.697c.111-.08.389-.22.718-.166");
}

.ma0zw7mze {
  d: path("m11.005 8.181l.041-.762c.174.023.309.184.309.38c0 .21-.157.38-.35.382Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.meeg_hbnd {
  cx: 20.796px;
  cy: 7.476px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.mh1m83zfh {
  d: path("m8.617 11.775l-.865-1.505h2.125l-.825 1.5a.25.25 0 0 1-.435.005Z");
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mngobgbzy {
  fill: var(--svg-color--605071, #605071);
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.moyj76b8y {
  d: path("M22.779 7.393c.027.037-.03.081-.096.13c-.065.05-.114.084-.142.047c-.027-.037.004-.106.07-.155c.065-.05.14-.06.168-.022Z");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mz2-1bfbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.897 7.193c.283 0 .522.195.587.46a.119.119 0 0 1-.116.147h-.967a.1.1 0 0 1-.1-.118a.608.608 0 0 1 .596-.489Z");
}

.n_1zi0c8z {
  d: path("M24.05 8.181c.014-.254.028-.508.04-.762c.175.023.31.184.31.38c0 .21-.157.38-.35.382Z");
}

.n1gy1w_fx {
  d: path("M9.762 7.31a.387.387 0 0 1 .373.49h-.748a.389.389 0 0 1 .375-.49Z");
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nykqrqb8m {
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o7pqjkb6j {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.352 6.697c.111-.08.39-.22.718-.166");
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ocp3d13tt {
  d: path("M21.266 7.652c0-.125-.101-.208-.129-.233l-.125.12l.077.157l.177-.043Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pndrqcxcx {
  fill: var(--svg-color--533634, #533634);
  d: path("M21.96 5.48a1.09 1.09 0 0 1-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573a2.04 2.04 0 0 1 .196-.041c.467-.076.808.343.808.816v.185l-.01.006Z");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qdtbq7bif {
  stroke: var(--svg-color--b68e7e, #B68E7E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.724 12.31l1.083.627c.194.1.579.44.57 1.002");
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qs8js6b0o {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m21.694 7.605l-.23.798c-.047.164.066.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.qut0ht_ps {
  d: path("m5.915 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy5kkb6yn {
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r5tyubbzf {
  d: path("m21.694 7.605l-.23.798c-.047.164.066.328.225.328h.341c.16 0 .273-.167.226-.328l-.23-.798c-.05-.176-.28-.176-.332 0Z");
}

.rdymgqtsv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
}

.rei3gtbmc {
  d: path("M19.672 7.107a.698.698 0 0 0 .056 1.39a33.967 33.967 0 0 1-.056-1.39Z");
}

.rfl05o_kt {
  d: path("M23.152 7.647a.364.364 0 0 0-.1-.2l-.113.123l.05.099l.163-.022Z");
}

.rh00e0bdu {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.815 9.171c-.22 0-.427-.052-.601-.142c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .687-.367c.037-.056-.027-.12-.086-.09c-.174.09-.379.142-.601.142Z");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rtm0-3azz {
  stop-color: var(--svg-color--9e7669, #9E7669);
}

.rx79cpb0u {
  d: path("M9.733 7.393c.028.037-.03.081-.095.13c-.066.05-.114.084-.142.047c-.028-.037.003-.106.069-.155c.065-.05.14-.06.168-.022Z");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s5fqzlkek {
  fill: var(--svg-color--725050, #725050);
  d: path("M10.722 5.48h-.926a.215.215 0 1 1 .034-.427c.24.038.56.091.774.144c.483.12.617.356.654.524a.674.674 0 0 0-.536-.24Z");
}

.s82a0vb9b {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.778 7.193a.606.606 0 0 0-.588.46a.119.119 0 0 0 .116.147h.968a.1.1 0 0 0 .098-.118a.608.608 0 0 0-.594-.489Z");
}

.sbcwsbc2z {
  stroke: var(--svg-color--b08b7e, #B08B7E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.94 70.94 0 0 0 1.555 1.415");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.skdh8c8wf {
  d: path("m18.96 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.sp4hzm5xt {
  fill: var(--svg-color--563936, #563936);
  d: path("m11.075 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.785.22 1.095.422c.756.493.624 1.383.226 1.801Z");
}

.syv7enbxw {
  d: path("M23.968 8.457a.711.711 0 0 0 .393-.134v.404a.943.943 0 0 1-.582.876c.074-.158.125-.329.15-.512l.04-.634Z");
}

.t_og1nq1i {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m8.64 7.69l-.256.797c-.043.164.062.328.21.328h.318c.149 0 .254-.166.21-.328l-.215-.797c-.046-.177-.218-.177-.266 0Z");
}

.t1dkn1b9a {
  d: path("M21.86 9.171c-.22 0-.427-.052-.601-.142c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .686-.367c.038-.056-.026-.12-.085-.09c-.174.09-.379.142-.601.142Z");
}

.tfw8ds16k {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.982 3.273c.221.71.522 1.166.644 1.305l.633-.242c-.013-.183-.096-.709-.324-1.356c-.286-.808-.579-1.09-.875-.996c-.211.086-.356.403-.078 1.29Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tjubatb2f {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.398 1.534c.12 0 .206-.12.166-.234l-.564-1.607Z");
}

.toow9ybtl {
  d: path("M10.923 8.457a.711.711 0 0 0 .392-.134v.404c0 .387-.23.733-.581.876a1.83 1.83 0 0 0 .15-.512l.039-.634Z");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ui16d5_tg {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29Z");
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v_jtpob4z {
  fill: var(--svg-color--000, #000);
  d: path("M21.134 7.698a.22.22 0 0 0-.221-.222a.22.22 0 0 0-.197.324h.392a.22.22 0 0 0 .026-.102Z");
}

.v145rzbrq {
  cx: 7.751px;
  cy: 7.476px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vns6nwbag {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m21.686 7.69l-.256.797c-.044.164.06.328.21.328h.317c.149 0 .254-.166.21-.328l-.215-.797c-.045-.177-.218-.177-.266 0Z");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vsmo47b5i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.779 7.393c.027.037-.03.081-.096.13c-.065.05-.114.084-.142.047c-.027-.037.004-.106.07-.155c.065-.05.14-.06.168-.022Z");
}

.vvah7_hxr {
  stop-color: var(--svg-color--ae8474, #AE8474);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w9jofw35x {
  stop-color: var(--svg-color--c09084, #C09084);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x_q13sb6n {
  d: path("M10.95 8.497c.028-.462.056-.923.08-1.385a.698.698 0 0 1-.08 1.385Z");
}

.x-wewjb5a {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.42 6.673a1.005 1.005 0 0 0-.718-.166");
}

.x4l_iofys {
  d: path("m11.075 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.785.22 1.095.422c.756.493.624 1.383.226 1.801Z");
}

.x77uznh9a {
  stroke: var(--svg-color--b08b7e, #B08B7E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.985 13.917c-.088.073-.193.29.094.57a70.98 70.98 0 0 0 1.555 1.415");
}

.xbp56ebtm {
  d: path("M10.107 7.647a.364.364 0 0 0-.1-.2l-.113.123l.05.099l.163-.022Z");
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.xh8imlblg {
  stop-color: var(--svg-color--8a4c72, #8A4C72);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xrds8ebpk {
  fill: var(--svg-color--000, #000);
  d: path("M22.585 7.698a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102Z");
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y_jvuobbm {
  fill: var(--svg-color--605071, #605071);
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.y1fkzut6k {
  d: path("M21.96 5.48a1.09 1.09 0 0 1-.028-.06a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.732c0-.465.339-.7.555-.85c.061-.042.112-.078.143-.11l.044-.045c.151-.161.421-.448.893-.573a2.04 2.04 0 0 1 .196-.041c.467-.076.808.343.808.816v.185l-.01.006Z");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yf8e95b_r {
  stop-color: var(--svg-color--966b64, #966B64);
}

.ygpxv2fle {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M7.335 6.575a1.203 1.203 0 0 1 .754-.156a.12.12 0 0 1-.029.24a.962.962 0 0 0-.634.144l-.007.005h-.001a.12.12 0 0 1-.147-.19l.064-.043Z");
}

.yjw08ccab {
  fill: var(--svg-color--563936, #563936);
  d: path("m24.12 6.896l-.012-.273a.637.637 0 0 0-.61-.619h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.784.22 1.095.422c.756.493.624 1.383.225 1.801Z");
}

.yrn5k97fg {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.z1un_4z8x {
  d: path("M22.807 7.31a.387.387 0 0 1 .373.49h-.748a.389.389 0 0 1 .375-.49Z");
}

.z264cr8wh {
  fill: var(--svg-color--000, #000);
  d: path("M8.09 7.698a.22.22 0 0 0-.223-.222a.22.22 0 0 0-.197.324h.393a.22.22 0 0 0 .026-.102Z");
}

.z3fl6nbuc {
  fill: var(--svg-color--c59b8a, #C59B8A);
  d: path("m11.496 20.164l.823-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.z44b3ob9l {
  d: path("M6.627 7.107a.698.698 0 0 0 .056 1.39a33.913 33.913 0 0 1-.056-1.39Z");
}

.zanlt2b3w {
  d: path("M10.92 5.034a1.028 1.028 0 0 1 .504 1.552a.676.676 0 0 0-.117.379v.515a.756.756 0 0 0-.29-.116l.034-.697a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465l.014.667a.742.742 0 0 0-.312.114v-.52a.676.676 0 0 0-.118-.38a1.037 1.037 0 0 1-.062-1.06c.127-.24.332-.407.564-.489c.248-.088.46-.255.6-.481a1.009 1.009 0 0 1 1.254-.396a.646.646 0 0 0 .517 0a1.008 1.008 0 0 1 1.258.41c.134.22.343.381.587.465Z");
}

.zdbmkmbsu {
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.zjev50bzf {
  d: path("M19.767 9.114a1.698 1.698 0 0 0 1.685 1.477h.819c.853 0 1.573-.63 1.685-1.477c.051-.817.102-1.63.14-2.447a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465c0 .807.051 1.601.104 2.41Z");
}

.zmosh3beg {
  d: path("M7.867 7.31a.387.387 0 0 0-.373.49h.748a.39.39 0 0 0-.375-.49Z");
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
