<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" class="skdh8c8wf"/><path fill="url(#svgIDb)" class="skdh8c8wf"/><path fill="url(#svgIDc)" class="qut0ht_ps"/><path fill="url(#svgIDd)" class="qut0ht_ps"/><g filter="url(#svgIDe)"><path class="jaasi8b4f"/></g><g filter="url(#svgIDf)"><path class="z78u0tbjp"/></g><g filter="url(#svgIDg)"><path class="ocjhgybgx"/></g><g filter="url(#svgIDh)"><path class="jcp6wzblx"/></g><path fill="url(#svgIDi)" class="g1-cakgjb"/><path fill="url(#svgIDj)" class="g1-cakgjb"/><path fill="url(#svgIDk)" class="xbx983bqi"/><path fill="url(#svgIDl)" class="xbx983bqi"/><path fill="url(#svgIDm)" class="tjubatb2f"/><path fill="url(#svgIDn)" class="tjubatb2f"/><path fill="url(#svgIDo)" class="c65lz4_ey"/><path fill="url(#svgIDp)" class="c65lz4_ey"/><circle class="f5qs1xbvv"/><circle class="v2km0iban"/><g filter="url(#svgIDq)"><path clip-rule="evenodd" class="rvhaf89mo"/></g><g filter="url(#svgIDr)"><path clip-rule="evenodd" class="s6sao6bdm"/></g><circle fill="url(#svgIDs)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><circle fill="url(#svgIDt)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g clip-rule="evenodd" filter="url(#svgIDu)" class="d2kvgvbvc"><path class="wgnyu7bnl"/><path fill="url(#svgIDv)" class="lp6j63-gu"/></g><g clip-rule="evenodd" filter="url(#svgIDw)" class="d2kvgvbvc"><path class="j_gcajbrp"/><path fill="url(#svgIDx)" class="sqcrd6aiu"/></g><path fill="url(#svgIDy)" class="ldd357aax"/><path fill="url(#svgIDz)" class="ldd357aax"/><path fill="url(#svgIDA)" class="c-ymhfbrh"/><path fill="url(#svgIDB)" class="c-ymhfbrh"/><g filter="url(#svgIDC)"><path class="fx5kzlbgl"/></g><g filter="url(#svgIDD)"><path class="nrrx0s8-f"/></g><path class="mngobgbzy"/><path fill="url(#svgIDE)" class="j7sojhblo"/><path class="y_jvuobbm"/><path fill="url(#svgIDF)" class="qy5kkb6yn"/><g filter="url(#svgIDG)"><path class="g6a574b3m"/></g><g filter="url(#svgIDH)"><path class="yrn5k97fg"/></g><path fill="url(#svgIDI)" class="nykqrqb8m"/><path fill="url(#svgIDJ)" class="nykqrqb8m"/><path fill="url(#svgIDK)" class="nykqrqb8m"/><path fill="url(#svgIDL)" class="nykqrqb8m"/><path fill="url(#svgIDM)" class="nykqrqb8m"/><path fill="url(#svgIDN)" class="zdbmkmbsu"/><path fill="url(#svgIDO)" class="zdbmkmbsu"/><path fill="url(#svgIDP)" class="zdbmkmbsu"/><path fill="url(#svgIDQ)" class="zdbmkmbsu"/><path fill="url(#svgIDR)" class="zdbmkmbsu"/><path fill="url(#svgIDS)" class="jaeg0gihu"/><path fill="url(#svgIDT)" class="mh1m83zfh"/><g filter="url(#svgIDU)"><path class="v-s4vkbbr"/></g><g filter="url(#svgIDV)"><path class="hj3gllh6o"/></g><path fill="url(#svgIDW)" class="g-b3iwvab"/><path fill="url(#svgIDX)" class="hox0ogbfq"/><path fill="url(#svgIDY)" class="g-d3cpbci"/><path fill="url(#svgIDZ)" class="jve9lcb6u"/><g filter="url(#svgIDaa)"><path fill="url(#svgIDab)" class="vnw38zbkj"/></g><g filter="url(#svgIDac)"><path fill="url(#svgIDad)" class="qqd8ljboe"/></g><path fill="url(#svgIDae)" class="vnw38zbkj"/><path fill="url(#svgIDaf)" class="vnw38zbkj"/><path fill="url(#svgIDag)" class="vnw38zbkj"/><path fill="url(#svgIDah)" class="vnw38zbkj"/><path fill="url(#svgIDai)" class="vnw38zbkj"/><path fill="url(#svgIDaj)" class="vnw38zbkj"/><path fill="url(#svgIDak)" class="vnw38zbkj"/><path fill="url(#svgIDal)" class="vnw38zbkj"/><path fill="url(#svgIDam)" class="vnw38zbkj"/><path fill="url(#svgIDan)" class="qqd8ljboe"/><path fill="url(#svgIDao)" class="qqd8ljboe"/><path fill="url(#svgIDap)" class="qqd8ljboe"/><path fill="url(#svgIDaq)" class="qqd8ljboe"/><path fill="url(#svgIDar)" class="qqd8ljboe"/><path fill="url(#svgIDas)" class="qqd8ljboe"/><path fill="url(#svgIDat)" class="qqd8ljboe"/><path fill="url(#svgIDau)" class="qqd8ljboe"/><path fill="url(#svgIDav)" class="qqd8ljboe"/><g filter="url(#svgIDaw)"><path class="hj99vhb-d"/></g><g filter="url(#svgIDax)"><path class="ypwa00bgf"/></g><g filter="url(#svgIDay)"><path class="k04hp0t7p"/><path fill="url(#svgIDaz)" class="ri00zbcfb"/><path fill="url(#svgIDaA)" class="ri00zbcfb"/><path fill="url(#svgIDaB)" class="ri00zbcfb"/><path fill="url(#svgIDaC)" class="ri00zbcfb"/><path fill="url(#svgIDaD)" class="ri00zbcfb"/></g><g filter="url(#svgIDaE)"><path class="k77mc556b"/><path fill="url(#svgIDaF)" class="ws87j3bev"/><path fill="url(#svgIDaG)" class="ws87j3bev"/><path fill="url(#svgIDaH)" class="ws87j3bev"/><path fill="url(#svgIDaI)" class="ws87j3bev"/><path fill="url(#svgIDaJ)" class="ws87j3bev"/></g><g filter="url(#svgIDaK)"><path stroke="url(#svgIDaL)" class="r-npajbwk"/></g><g filter="url(#svgIDaM)"><path stroke="url(#svgIDaN)" class="dwumpsbty"/></g><path fill="url(#svgIDaO)" class="qf196ebdr"/><path fill="url(#svgIDaP)" class="n5ns48bfj"/><g filter="url(#svgIDaQ)"><path fill="url(#svgIDaR)" class="jpo-rv9en"/><path fill="url(#svgIDaS)" class="jpo-rv9en"/><path fill="url(#svgIDaT)" class="jpo-rv9en"/><path fill="url(#svgIDaU)" class="jpo-rv9en"/><path fill="url(#svgIDaV)" class="jpo-rv9en"/></g><g filter="url(#svgIDaW)"><path fill="url(#svgIDaX)" class="fjuoal_4l"/><path fill="url(#svgIDaY)" class="fjuoal_4l"/><path fill="url(#svgIDaZ)" class="fjuoal_4l"/><path fill="url(#svgIDba)" class="fjuoal_4l"/><path fill="url(#svgIDbb)" class="fjuoal_4l"/></g><g filter="url(#svgIDbc)"><path class="iuo_ypwlx"/></g><g filter="url(#svgIDbd)"><path class="u7pfdacda"/></g><g filter="url(#svgIDbe)"><path class="ze3cmz88b"/></g><g filter="url(#svgIDbf)"><path class="ruygvfbyz"/></g><g filter="url(#svgIDbg)"><path class="jq26gibow"/><path fill="url(#svgIDbh)" class="utpitec7f"/><path fill="url(#svgIDbi)" class="utpitec7f"/></g><g filter="url(#svgIDbj)"><path class="vytf_obly"/><path fill="url(#svgIDbk)" class="a_t-x2slk"/><path fill="url(#svgIDbl)" class="a_t-x2slk"/></g><g filter="url(#svgIDbm)"><path class="e0kaqubrn"/><path fill="url(#svgIDbn)" class="l_4m7sbzg"/></g><g filter="url(#svgIDbo)"><path class="m093owzoo"/><path fill="url(#svgIDbp)" class="esuamwbli"/></g><path class="v902jhbyk"/><path fill="url(#svgIDbq)" class="d92jpiq8u"/><path fill="url(#svgIDbr)" class="fu4lq347f"/><path class="wr4-wibgw"/><g filter="url(#svgIDbs)"><path class="jv2hyt9oy"/><path fill="url(#svgIDbt)" class="ln7z91brh"/></g><g filter="url(#svgIDbu)"><path class="u2vz14b9e"/><path fill="url(#svgIDbv)" class="f0_o78z1h"/></g><g filter="url(#svgIDbw)"><path fill="url(#svgIDbx)" class="d9jcakr9c"/></g><g filter="url(#svgIDby)"><path fill="url(#svgIDbz)" class="jku41c19t"/></g><path class="jsq3508ai"/><path fill="url(#svgIDbA)" class="zur4xmb7i"/><path fill="url(#svgIDbB)" class="h8zdekbde"/><path class="h6tjyg93v"/><g filter="url(#svgIDbC)"><path fill="url(#svgIDbD)" class="smq_n71ig"/></g><g filter="url(#svgIDbE)"><path fill="url(#svgIDbF)" class="pcumab9zp"/></g><g filter="url(#svgIDbG)" transform="rotate(-27.914 20.796 7.485)"><ellipse class="bglzgonbl"/><ellipse fill="url(#svgIDbH)" class="f490zrwwa"/></g><g filter="url(#svgIDbI)" transform="rotate(-27.914 7.75 7.485)"><ellipse class="h2wts5blg"/><ellipse fill="url(#svgIDbJ)" class="g4m0z5byx"/></g><path fill="url(#svgIDbK)" class="cpye2rbxj"/><path fill="url(#svgIDbL)" class="cpye2rbxj"/><path fill="url(#svgIDbM)" class="cpye2rbxj"/><path fill="url(#svgIDbN)" class="cpye2rbxj"/><path fill="url(#svgIDbO)" class="w6m8kfbci"/><path fill="url(#svgIDbP)" class="w6m8kfbci"/><path fill="url(#svgIDbQ)" class="w6m8kfbci"/><path fill="url(#svgIDbR)" class="w6m8kfbci"/><path fill="url(#svgIDbS)" class="clhg74ppl"/><path fill="url(#svgIDbT)" class="clhg74ppl"/><path fill="url(#svgIDbU)" class="bc1oh9b6v"/><path fill="url(#svgIDbV)" class="bc1oh9b6v"/><g filter="url(#svgIDbW)"><path fill="url(#svgIDbX)" class="xiesyilgk"/></g><g filter="url(#svgIDbY)"><path fill="url(#svgIDbZ)" class="ljry9yyut"/></g><g filter="url(#svgIDca)"><path fill="url(#svgIDcb)" class="e_ke-ibnl"/></g><g filter="url(#svgIDcc)"><path fill="url(#svgIDcd)" class="un4jk-8pt"/></g><g filter="url(#svgIDce)"><path class="lx12w890o"/></g><g filter="url(#svgIDcf)"><path class="qud_o7bfq"/></g><g filter="url(#svgIDcg)"><path class="fhxu-4bqu"/></g><g filter="url(#svgIDch)"><path class="hrzu3nbcu"/></g><g filter="url(#svgIDci)"><path class="fb0e9bc2g"/></g><g filter="url(#svgIDcj)"><path class="hgt_f1i1r"/></g><g filter="url(#svgIDck)"><path class="tfw8ds16k"/></g><g filter="url(#svgIDcl)"><path class="e-c-ph2vh"/></g><g filter="url(#svgIDcm)"><path class="iyrh5w2dl"/></g><g filter="url(#svgIDcn)"><path class="ui16d5_tg"/></g><g filter="url(#svgIDco)"><path fill="url(#svgIDcp)" class="ecm9b1coi"/></g><g filter="url(#svgIDcq)"><path fill="url(#svgIDcr)" class="h7h8n338b"/></g><defs><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDn" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDs" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="yrxal2b8w"/><stop offset="1" class="iks-j-9-l"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="yrxal2b8w"/><stop offset="1" class="iks-j-9-l"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(157.797 12.832 9.57) scale(1.65389 2.1298)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="rotate(157.797 6.31 8.29) scale(1.65389 2.1298)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.493 3.115) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDL" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.284 10.168) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.02 -2.037) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDN" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.97 7.278) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.762 7.838) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.45766 -2.68928 1.12443 .19135 8.12 21)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDS" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="u0gzasb1f"/><stop offset=".902" class="mtb7t9jlr"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="u0gzasb1f"/><stop offset=".902" class="mtb7t9jlr"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(.32475 .87588 -1.04048 .38577 23.922 8.332)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="matrix(.32475 .87588 -1.04048 .38577 10.876 8.332)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(.64035 .20125 -.62088 1.97551 19.233 8.545)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(.64035 .20125 -.62088 1.97551 6.188 8.545)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26734 0 0 -4.0109 23.078 7.924)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26734 0 0 -4.0109 10.032 7.924)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="matrix(-.44336 5.38812 -4.46201 -.36716 22.546 5.359)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="svgIDag" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49804 .61633 0 22.921 7.355)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="svgIDah" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.4746 .51647 .00186 20.862 7.375)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 11.543 4.544) scale(3.69208 9.4314)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="svgIDaj" cx="0" cy="0" r="1" gradientTransform="matrix(1.76648 -1.14857 .42046 .64665 19.488 6.048)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="svgIDak" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 9.101 14.375) scale(1.08792 .43489)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 9.83 9.343) scale(1.46114 1.20629)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(-.44336 5.38812 -4.46201 -.36716 9.5 5.36)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49804 .61633 0 9.876 7.355)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.4746 .51647 .00186 7.817 7.375)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="svgIDar" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 5.02 4.339) scale(3.69208 9.4314)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="svgIDas" cx="0" cy="0" r="1" gradientTransform="rotate(-33.032 13.42 -7.84) scale(2.10705 .77133)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="svgIDat" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 2.578 8.437) scale(1.08792 .43489)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 3.308 5.665) scale(1.46114 1.20629)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10587 -.33273 0 22.062 8.514)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(-.65973 .30248 -.4861 -1.06023 22.113 8.267)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10587 -.33273 0 9.017 8.514)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="matrix(-.65973 .30248 -.4861 -1.06023 9.067 8.267)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="svgIDaO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31259 1.25761 0 21.86 9.459)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31259 1.25761 0 8.815 9.459)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51854 3.84021 0 19.592 6.67)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(.04946 -1.0897 1.93073 .08763 23.968 7.238)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02303 -.67285 .4939 -.75096 23.64 4.516)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 7.316 21.093) scale(.75055 1.73792)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51854 3.84021 0 6.547 6.67)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(.04946 -1.0897 1.93073 .08763 10.923 7.238)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02303 -.67285 .4939 -.75096 10.596 4.516)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="svgIDbb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 .794 9.437) scale(.75055 1.73792)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(-.95464 0 0 -.3543 21.97 4.805)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(1.39574 -2.20991 2.44836 1.54633 19.504 6.515)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(-.95464 0 0 -.3543 8.925 4.805)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(1.39574 -2.20991 2.44836 1.54633 6.46 6.515)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(1.40876 .16466 -.06894 .58982 22.618 5.819)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(1.40876 .16466 -.06894 .58982 9.573 5.819)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35187 -.5597 0 22.806 7.527)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35187 -.5597 0 9.761 7.527)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(-.10058 -.12962 .17845 -.13848 22.707 7.563)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(-.10058 -.12962 .17845 -.13848 9.662 7.563)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35189 -.55972 0 20.914 7.527)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35189 -.55972 0 7.868 7.527)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21429 .25758 -.00403 20.79 7.622)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21429 .25758 -.00403 7.744 7.622)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="rotate(74.347 6.965 19.5) scale(1.01039 .96399)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="matrix(.34166 -.46888 .39301 .28638 24.019 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(.25458 -.67242 .89845 .34016 24.068 7.843)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="rotate(74.347 .442 10.899) scale(1.01039 .96399)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="svgIDbQ" cx="0" cy="0" r="1" gradientTransform="matrix(.34166 -.46888 .393 .28638 10.974 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="svgIDbR" cx="0" cy="0" r="1" gradientTransform="matrix(.25458 -.67242 .89845 .34016 11.023 7.844)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="svgIDbT" cx="0" cy="0" r="1" gradientTransform="matrix(-.17906 .90038 -.88516 -.17604 19.577 7.605)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="svgIDbV" cx="0" cy="0" r="1" gradientTransform="matrix(-.17906 .90038 -.88516 -.17604 6.532 7.605)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="svgIDbX" cx="0" cy="0" r="1" gradientTransform="rotate(170.263 9.531 4.746) scale(.40329 .17788)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="svgIDbZ" cx="0" cy="0" r="1" gradientTransform="rotate(170.263 3.009 4.19) scale(.40329 .17788)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="svgIDe" width="6.578" height="10.091" x="23.071" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.121569 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDf" width="6.578" height="10.091" x="10.026" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.121569 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDg" width="4.976" height="9.579" x="24.041" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".25"/></filter><filter id="svgIDh" width="4.976" height="9.579" x="10.996" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".25"/></filter><filter id="svgIDq" width="5.896" height="7.11" x="15.796" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDr" width="5.896" height="7.11" x="2.751" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDu" width="5.996" height="6.96" x="22.312" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.105882 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDw" width="5.996" height="6.96" x="9.267" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.105882 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDC" width="2.703" height="2.68" x="25.244" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".2"/></filter><filter id="svgIDD" width="2.703" height="2.68" x="12.199" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".2"/></filter><filter id="svgIDG" width="9.692" height="11.056" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDH" width="9.692" height="11.056" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDU" width="2.793" height="3.034" x="16.366" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".2"/></filter><filter id="svgIDV" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".2"/></filter><filter id="svgIDaa" width="5.433" height="5.553" x="19.664" y="5.248" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDac" width="5.433" height="5.553" x="6.619" y="5.248" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDaw" width="2.758" height="3.258" x="20.42" y="6.566" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".5"/></filter><filter id="svgIDax" width="2.758" height="3.258" x="7.374" y="6.566" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".5"/></filter><filter id="svgIDay" width=".914" height="1.358" x="21.403" y="7.432" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".025"/></filter><filter id="svgIDaE" width=".914" height="1.358" x="8.357" y="7.432" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".025"/></filter><filter id="svgIDaK" width="1.896" height=".965" x="20.912" y="8.78" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".05"/></filter><filter id="svgIDaM" width="1.896" height=".965" x="7.867" y="8.78" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".05"/></filter><filter id="svgIDaQ" width="5.583" height="3.907" x="19.068" y="3.587" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDaW" width="5.583" height="3.907" x="6.023" y="3.587" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDbc" width="1.071" height=".63" x="22.549" y="6.213" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDbd" width="1.071" height=".63" x="9.504" y="6.213" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDbe" width="1.071" height=".623" x="20.269" y="6.219" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDbf" width="1.071" height=".623" x="7.224" y="6.219" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/></filter><filter id="svgIDbg" width="3.189" height="2.71" x="19.181" y="4.322" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feGaussianBlur result="effect2_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDbj" width="3.189" height="2.71" x="6.136" y="4.322" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feGaussianBlur result="effect2_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDbm" width="2.771" height="2.534" x="21.82" y="4.521" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feGaussianBlur result="effect2_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDbo" width="2.771" height="2.534" x="8.775" y="4.521" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feGaussianBlur result="effect2_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDbs" width=".455" height=".415" x="22.431" y="7.279" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".05"/></filter><filter id="svgIDbu" width=".455" height=".415" x="9.386" y="7.279" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".05"/></filter><filter id="svgIDbw" width=".613" height=".623" x="22.739" y="7.255" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".1"/></filter><filter id="svgIDby" width=".613" height=".623" x="9.694" y="7.255" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".1"/></filter><filter id="svgIDbC" width=".654" height=".678" x="20.812" y="7.228" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".1"/></filter><filter id="svgIDbE" width=".654" height=".678" x="7.767" y="7.228" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".1"/></filter><filter id="svgIDbG" width=".509" height=".419" x="20.541" y="7.276" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".05"/></filter><filter id="svgIDbI" width=".509" height=".419" x="7.496" y="7.276" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".05"/></filter><filter id="svgIDbW" width=".859" height="1.315" x="19.081" y="7.154" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".125"/></filter><filter id="svgIDbY" width=".859" height="1.315" x="6.036" y="7.154" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".125"/></filter><filter id="svgIDca" width="1.411" height="1.825" x="23.504" y="6.896" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".25"/></filter><filter id="svgIDcc" width="1.411" height="1.825" x="10.459" y="6.896" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".25"/></filter><filter id="svgIDce" width="1.118" height=".578" x="20.197" y="6.328" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDcf" width="1.118" height=".578" x="7.152" y="6.328" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDcg" width="1.118" height=".578" x="22.486" y="6.308" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDch" width="1.118" height=".578" x="9.441" y="6.308" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".075"/></filter><filter id="svgIDci" width="2.133" height="1.153" x="22.316" y="4.826" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".125"/></filter><filter id="svgIDcj" width="2.133" height="1.153" x="9.271" y="4.826" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_706" stdDeviation=".125"/></filter><filter id="svgIDck" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDcl" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDcm" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDcn" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDco" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><filter id="svgIDcq" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_706"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_706" result="effect2_innerShadow_4002_706"/></filter><linearGradient id="svgIDa" x1="18.96" x2="21.079" y1="24.13" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="jufkgjxmt"/></linearGradient><linearGradient id="svgIDb" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="vnco_-oam"/><stop offset="1" class="ily885bgj"/></linearGradient><linearGradient id="svgIDc" x1="5.915" x2="8.034" y1="24.13" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="jufkgjxmt"/></linearGradient><linearGradient id="svgIDd" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="vnco_-oam"/><stop offset="1" class="ily885bgj"/></linearGradient><linearGradient id="svgIDy" x1="18.383" x2="19.305" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDz" x1="18.899" x2="18.539" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDA" x1="5.338" x2="6.26" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDB" x1="5.854" x2="5.495" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDE" x1="25.133" x2="25.571" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDF" x1="12.088" x2="12.526" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDJ" x1="18.774" x2="19.446" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDO" x1="5.729" x2="6.401" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDae" x1="24.096" x2="22.209" y1="8.655" y2="8.655" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="svgIDam" x1="21.88" x2="21.88" y1="10.636" y2="10.358" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="svgIDan" x1="11.051" x2="9.164" y1="8.655" y2="8.655" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="svgIDav" x1="8.835" x2="8.835" y1="10.636" y2="10.358" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="svgIDaz" x1="22.224" x2="21.86" y1="8.217" y2="8.232" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="svgIDaB" x1="21.86" x2="21.86" y1="8.711" y2="8.509" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="svgIDaD" x1="21.86" x2="21.86" y1="7.429" y2="7.775" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="svgIDaF" x1="9.178" x2="8.815" y1="8.217" y2="8.232" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="svgIDaH" x1="8.815" x2="8.815" y1="8.711" y2="8.509" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="svgIDaJ" x1="8.815" x2="8.815" y1="7.429" y2="7.775" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="svgIDaL" x1="21.236" x2="21.477" y1="9.263" y2="9.03" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="svgIDaN" x1="8.19" x2="8.431" y1="9.263" y2="9.03" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="svgIDaR" x1="24.832" x2="19.795" y1="5.468" y2="5.468" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="svgIDaX" x1="11.786" x2="6.75" y1="5.468" y2="5.468" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="svgIDbx" x1="23.143" x2="23.007" y1="7.55" y2="7.634" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbz" x1="10.098" x2="9.962" y1="7.55" y2="7.634" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbD" x1="21.236" x2="21.1" y1="7.55" y2="7.634" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbF" x1="8.191" x2="8.055" y1="7.55" y2="7.634" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbK" x1="24.651" x2="24.128" y1="7.562" y2="8.506" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="svgIDbO" x1="11.606" x2="11.083" y1="7.562" y2="8.506" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="svgIDbS" x1="19.323" x2="19.955" y1="7.867" y2="7.812" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="svgIDbU" x1="6.278" x2="6.91" y1="7.867" y2="7.812" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="svgIDcb" x1="24.209" x2="24.209" y1="7.396" y2="8.222" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="svgIDcd" x1="11.164" x2="11.164" y1="7.396" y2="8.222" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="svgIDcp" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDcr" x1="10.698" x2="7.198" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-bunny-ears-dark" /></template>
<style>
.a_t-x2slk {
  d: path("m8.916 5.488l-.03-.059a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.733c0-.464.339-.7.555-.85c.061-.042.113-.077.144-.11l.043-.045c.151-.16.422-.447.893-.572c.066-.017.131-.031.196-.042c.467-.075.808.344.808.817v.184l-.01.006Z");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc1oh9b6v {
  d: path("M6.623 7.118a.698.698 0 0 0 .06 1.388a33.843 33.843 0 0 1-.06-1.388Z");
}

.bglzgonbl {
  cx: 20.796px;
  cy: 7.485px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.c-ymhfbrh {
  d: path("m5.26 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.814 1.37Z");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c65lz4_ey {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clhg74ppl {
  d: path("M19.668 7.118a.698.698 0 0 0 .06 1.388a33.879 33.879 0 0 1-.06-1.388Z");
}

.cpye2rbxj {
  d: path("M23.994 8.506c.029-.462.056-.923.08-1.385a.698.698 0 0 1-.08 1.385Z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d92jpiq8u {
  d: path("M22.807 7.32a.387.387 0 0 1 .373.489h-.748a.389.389 0 0 1 .375-.49Z");
}

.d9jcakr9c {
  d: path("M23.152 7.656a.364.364 0 0 0-.1-.201l-.113.124l.05.099l.163-.022Z");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dwumpsbty {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.248 8.971A.141.141 0 0 0 8.08 9a.134.134 0 0 0-.014.17c.158.24.435.4.749.4s.59-.16.749-.4L9.5 9.128l.063.042a.135.135 0 0 0-.015-.171a.142.142 0 0 0-.168-.028a1.222 1.222 0 0 1-.566.134c-.209 0-.404-.049-.567-.134Z");
}

.e_ke-ibnl {
  d: path("m24.004 8.222l.048-.826a.414.414 0 0 1-.048.826Z");
}

.e-c-ph2vh {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.632-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0kaqubrn {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m24.12 6.905l-.012-.274a.637.637 0 0 0-.61-.618h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.784.22 1.095.422c.756.493.624 1.382.225 1.801Z");
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

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.esuamwbli {
  d: path("m11.075 6.905l-.012-.274a.637.637 0 0 0-.61-.618h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.785.22 1.095.422c.756.493.624 1.382.226 1.801Z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f0_o78z1h {
  d: path("M9.733 7.401c.028.037-.03.082-.095.131c-.066.05-.114.084-.142.047c-.028-.037.003-.107.069-.156c.065-.049.14-.058.168-.022Z");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f490zrwwa {
  cx: 20.796px;
  cy: 7.485px;
  rx: 0.169px;
  ry: 0.086px;
}

.f5qs1xbvv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--2d151b, #2D151B);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fb0e9bc2g {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M23.678 5.496h-.902a.21.21 0 1 1 .033-.417c.234.037.545.09.753.141c.471.117.601.346.638.51a.656.656 0 0 0-.522-.234Z");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fhxu-4bqu {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.404 6.686a1.004 1.004 0 0 0-.718-.166");
}

.fjuoal_4l {
  d: path("M10.92 5.043a1.028 1.028 0 0 1 .504 1.552a.676.676 0 0 0-.117.379v.515a.757.757 0 0 0-.29-.116l.034-.697a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465l.014.667a.742.742 0 0 0-.312.114v-.52a.676.676 0 0 0-.118-.38a1.037 1.037 0 0 1-.062-1.06c.127-.24.332-.407.564-.489c.248-.088.46-.256.6-.481a1.009 1.009 0 0 1 1.254-.396a.646.646 0 0 0 .517 0a1.009 1.009 0 0 1 1.258.41c.134.22.343.381.587.465Z");
}

.ft5dv1b6b {
  fill: none;
}

.fu4lq347f {
  d: path("M9.762 7.32a.387.387 0 0 1 .373.489h-.748a.389.389 0 0 1 .375-.49Z");
}

.fx5kzlbgl {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.77 12.31l1.083.627c.193.1.578.44.569 1.002");
}

.g-b3iwvab {
  d: path("M23.968 8.466a.711.711 0 0 0 .393-.134v.404a.944.944 0 0 1-.582.876c.074-.158.125-.33.15-.512l.04-.634Z");
}

.g-d3cpbci {
  d: path("M19.752 8.466a.712.712 0 0 1-.393-.134v.404c0 .387.23.732.582.876a1.772 1.772 0 0 1-.15-.512l-.04-.634Z");
}

.g1-cakgjb {
  d: path("m20.928 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g4m0z5byx {
  cx: 7.751px;
  cy: 7.485px;
  rx: 0.169px;
  ry: 0.086px;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g6a574b3m {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h2wts5blg {
  cx: 7.751px;
  cy: 7.485px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.h6tjyg93v {
  fill: var(--svg-color--000, #000);
  d: path("M21.134 7.707a.22.22 0 0 0-.221-.222a.22.22 0 0 0-.197.324h.392a.22.22 0 0 0 .026-.102Zm-13.044 0a.22.22 0 0 0-.223-.222a.22.22 0 0 0-.197.324h.393a.22.22 0 0 0 .026-.102Z");
}

.h7h8n338b {
  d: path("M11.048 5.75c.019.097-.101.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.h8zdekbde {
  d: path("M7.867 7.32a.387.387 0 0 0-.373.489h.748a.39.39 0 0 0-.375-.49Z");
}

.hgt_f1i1r {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M10.633 5.496h-.902a.21.21 0 1 1 .033-.417c.234.037.545.09.753.141c.471.117.601.346.638.51a.657.657 0 0 0-.522-.234Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hj3gllh6o {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.94 70.94 0 0 0 1.555 1.415");
}

.hj99vhb-d {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m21.686 7.699l-.256.797c-.044.164.061.328.21.328h.317c.149 0 .254-.166.21-.328l-.214-.797c-.046-.177-.219-.177-.267 0Z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hox0ogbfq {
  d: path("M10.923 8.466a.711.711 0 0 0 .392-.134v.404c0 .387-.23.732-.581.876c.074-.158.124-.33.15-.512l.04-.634Z");
}

.hrzu3nbcu {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.36 6.686a1.008 1.008 0 0 0-.719-.166");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iks-j-9-l {
  stop-color: var(--svg-color--382032, #382032);
}

.ily885bgj {
  stop-color: var(--svg-color--55423e, #55423E);
  stop-opacity: 0;
}

.iuo_ypwlx {
  fill: var(--svg-color--202020, #202020);
  d: path("M23.479 6.632a.805.805 0 0 0-.298-.179a1.25 1.25 0 0 0-.526-.025a.12.12 0 1 0 .029.24c.209-.026.336-.013.424.015a.56.56 0 0 1 .213.13a.12.12 0 0 0 .158-.181Z");
}

.iyrh5w2dl {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.816 3.273c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.izaac2bev {
  stop-color: var(--svg-color--6a5654, #6A5654);
  stop-opacity: 0;
}

.j_gcajbrp {
  fill: var(--svg-color--432a2f, #432A2F);
  d: path("M9.369 10.716a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.575-2.015a.8.8 0 0 0-1.088.308Z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sojhblo {
  d: path("m25.549 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.jaasi8b4f {
  fill: var(--svg-color--442a2e, #442A2E);
  d: path("m25.774 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.jaeg0gihu {
  d: path("m21.662 11.775l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005Z");
}

.jcp6wzblx {
  fill: var(--svg-color--655251, #655251);
  d: path("m11.496 20.164l.823-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jku41c19t {
  d: path("M10.107 7.656a.364.364 0 0 0-.1-.201l-.113.124l.05.099l.163-.022Z");
}

.jpo-rv9en {
  d: path("M23.965 5.043a1.028 1.028 0 0 1 .504 1.552a.676.676 0 0 0-.117.379v.515a.756.756 0 0 0-.29-.116l.034-.697a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.959-.626a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465l.014.667a.742.742 0 0 0-.312.114v-.52a.676.676 0 0 0-.117-.38a1.037 1.037 0 0 1-.063-1.06c.127-.24.332-.407.564-.489c.248-.088.46-.256.6-.481a1.008 1.008 0 0 1 1.254-.396a.646.646 0 0 0 .518 0a1.008 1.008 0 0 1 1.258.41a1.1 1.1 0 0 0 .586.465Z");
}

.jq26gibow {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M21.96 5.488c-.01-.02-.02-.039-.028-.059a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.733c0-.464.339-.7.555-.85c.061-.042.112-.077.143-.11l.044-.045c.151-.16.421-.447.893-.572c.066-.017.131-.031.196-.042c.467-.075.808.344.808.817v.184l-.01.006Z");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsq3508ai {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.823 7.202a.606.606 0 0 0-.588.459a.119.119 0 0 0 .116.148h.968a.1.1 0 0 0 .099-.118a.608.608 0 0 0-.595-.49Zm-13.045 0a.606.606 0 0 0-.588.459a.119.119 0 0 0 .116.148h.968a.1.1 0 0 0 .098-.118a.608.608 0 0 0-.594-.49Z");
}

.jufkgjxmt {
  stop-color: var(--svg-color--533a3b, #533A3B);
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.jv2hyt9oy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.779 7.401c.027.037-.03.082-.096.131c-.065.05-.114.084-.142.047c-.027-.037.004-.107.07-.156c.065-.049.14-.058.168-.022Z");
}

.jve9lcb6u {
  d: path("M6.706 8.466a.711.711 0 0 1-.392-.134v.404c0 .387.23.732.582.876a1.773 1.773 0 0 1-.15-.512l-.04-.634Z");
}

.k04hp0t7p {
  fill: var(--svg-color--402929, #402929);
  d: path("m21.694 7.614l-.23.797c-.047.164.066.328.225.328h.341c.16 0 .273-.166.226-.328l-.23-.797c-.05-.177-.28-.177-.332 0Z");
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k77mc556b {
  fill: var(--svg-color--402929, #402929);
  d: path("m8.649 7.614l-.23.797c-.048.164.065.328.225.328h.341c.16 0 .273-.166.226-.328l-.23-.797c-.05-.177-.28-.177-.332 0Z");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.kr_eiac3t {
  r: 0.766px;
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l_4m7sbzg {
  d: path("m24.12 6.905l-.012-.274a.637.637 0 0 0-.61-.618h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.784.22 1.095.422c.756.493.624 1.382.225 1.801Z");
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.ldd357aax {
  d: path("m18.305 13.39l2.828-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612l.813 1.37Z");
}

.lenvnubyg {
  stop-color: var(--svg-color--3d2728, #3D2728);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljry9yyut {
  d: path("M6.61 7.404a.415.415 0 0 0 .035.815a33.795 33.795 0 0 1-.036-.815Z");
}

.ln7z91brh {
  d: path("M22.779 7.401c.027.037-.03.082-.096.131c-.065.05-.114.084-.142.047c-.027-.037.004-.107.07-.156c.065-.049.14-.058.168-.022Z");
}

.lp6j63-gu {
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.974-1.72c.93-.82.855-2.148-.348-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lx12w890o {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.397 6.706c.111-.08.389-.221.718-.166");
}

.m093owzoo {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m11.075 6.905l-.012-.274a.637.637 0 0 0-.61-.618h-.607a1.05 1.05 0 0 1-.921-.546s.312-.902.83-.785c.38.085.785.22 1.095.422c.756.493.624 1.382.226 1.801Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
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

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mtb7t9jlr {
  stop-color: var(--svg-color--4c3534, #4C3534);
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n5ns48bfj {
  d: path("M8.815 9.18c-.22 0-.427-.052-.601-.142c-.06-.03-.124.036-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .686-.367c.038-.056-.026-.12-.086-.09c-.173.09-.378.142-.6.142Z");
}

.nrrx0s8-f {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.724 12.31l1.083.627c.194.1.579.44.57 1.002");
}

.nykqrqb8m {
  d: path("M21.832 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.22 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.ocjhgybgx {
  fill: var(--svg-color--655251, #655251);
  d: path("m24.54 20.164l.824-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pcumab9zp {
  d: path("M8.221 7.661c0-.125-.102-.208-.13-.233l-.124.12l.077.157l.177-.044Z");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qf196ebdr {
  d: path("M21.86 9.18c-.22 0-.427-.052-.601-.142c-.06-.03-.123.036-.086.09a.82.82 0 0 0 .687.367a.821.821 0 0 0 .686-.367c.038-.056-.026-.12-.085-.09c-.174.09-.379.142-.601.142Z");
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qqd8ljboe {
  d: path("M6.722 9.123A1.698 1.698 0 0 0 8.407 10.6h.818c.854 0 1.574-.63 1.686-1.477c.05-.817.102-1.63.14-2.447a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465c0 .807.051 1.601.104 2.41Z");
}

.qud_o7bfq {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.352 6.706c.111-.08.39-.221.718-.166");
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

.r-npajbwk {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M21.294 8.971h-.001a.141.141 0 0 0-.168.029a.134.134 0 0 0-.014.17c.159.24.435.4.749.4s.59-.16.749-.4l-.063-.042l.063.042a.135.135 0 0 0-.015-.171a.142.142 0 0 0-.167-.028h-.001a1.222 1.222 0 0 1-.566.134c-.209 0-.404-.049-.566-.134Z");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.ri00zbcfb {
  d: path("m21.694 7.614l-.23.797c-.047.164.066.328.225.328h.341c.16 0 .273-.166.226-.328l-.23-.797c-.05-.177-.28-.177-.332 0Z");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.ruygvfbyz {
  fill: var(--svg-color--202020, #202020);
  d: path("M7.336 6.584a1.203 1.203 0 0 1 .754-.156a.12.12 0 0 1-.03.24a.962.962 0 0 0-.634.143l-.007.006a.12.12 0 0 1-.148-.19l.065-.043Z");
}

.rvhaf89mo {
  fill: var(--svg-color--462f33, #462F33);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.s6sao6bdm {
  fill: var(--svg-color--462f33, #462F33);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.skdh8c8wf {
  d: path("m18.96 20.239l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.smq_n71ig {
  d: path("M21.266 7.661c0-.125-.101-.208-.129-.233l-.125.12l.077.157l.177-.044Z");
}

.sqcrd6aiu {
  d: path("M9.369 10.716a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.575-2.015a.8.8 0 0 0-1.088.308Z");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
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

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u0gzasb1f {
  stop-color: var(--svg-color--231011, #231011);
}

.u2vz14b9e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.733 7.401c.028.037-.03.082-.095.131c-.066.05-.114.084-.142.047c-.028-.037.003-.107.069-.156c.065-.049.14-.058.168-.022Z");
}

.u7pfdacda {
  fill: var(--svg-color--202020, #202020);
  d: path("M10.434 6.632a.805.805 0 0 0-.298-.179a1.25 1.25 0 0 0-.526-.025a.12.12 0 1 0 .029.24c.209-.026.337-.013.425.015a.57.57 0 0 1 .212.13a.12.12 0 0 0 .158-.181Z");
}

.ui16d5_tg {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29Z");
}

.un4jk-8pt {
  d: path("m10.959 8.222l.048-.826a.414.414 0 0 1-.048.826Z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.utpitec7f {
  d: path("M21.96 5.488c-.01-.02-.02-.039-.028-.059a.288.288 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.733c0-.464.339-.7.555-.85c.061-.042.112-.077.143-.11l.044-.045c.151-.16.421-.447.893-.572c.066-.017.131-.031.196-.042c.467-.075.808.344.808.817v.184l-.01.006Z");
}

.v-s4vkbbr {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.985 13.917c-.088.073-.193.29.094.57a70.98 70.98 0 0 0 1.555 1.415");
}

.v2km0iban {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--2d151b, #2D151B);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v902jhbyk {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.897 7.202c.283 0 .522.195.587.459a.119.119 0 0 1-.116.148h-.967a.1.1 0 0 1-.1-.118a.61.61 0 0 1 .596-.49Zm-13.045 0c.283 0 .522.195.587.459a.119.119 0 0 1-.116.148h-.967a.1.1 0 0 1-.099-.118c.055-.278.3-.49.595-.49Z");
}

.vnco_-oam {
  stop-color: var(--svg-color--55423e, #55423E);
}

.vnw38zbkj {
  d: path("M19.767 9.123a1.698 1.698 0 0 0 1.685 1.477h.819c.853 0 1.573-.63 1.685-1.477c.051-.817.102-1.63.14-2.447a.629.629 0 0 0-.598-.621h-.607a1.05 1.05 0 0 1-.96-.626a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465c0 .807.051 1.601.104 2.41Z");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vytf_obly {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m8.916 5.488l-.03-.059a.288.288 0 0 0-.266-.181h-.552c-.8 0-1.45.656-1.45 1.465v.12c-.147-.113-.332-.35-.332-.733c0-.464.339-.7.555-.85c.061-.042.113-.077.144-.11l.043-.045c.151-.16.422-.447.893-.572c.066-.017.131-.031.196-.042c.467-.075.808.344.808.817v.184l-.01.006Z");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w6m8kfbci {
  d: path("M10.95 8.506c.028-.462.056-.923.08-1.385a.698.698 0 0 1-.08 1.385Z");
}

.wgnyu7bnl {
  fill: var(--svg-color--432a2f, #432A2F);
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.974-1.72c.93-.82.855-2.148-.348-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.wr4-wibgw {
  fill: var(--svg-color--000, #000);
  d: path("M22.585 7.707a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102Zm-13.045 0a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102Z");
}

.ws87j3bev {
  d: path("m8.649 7.614l-.23.797c-.048.164.065.328.225.328h.341c.16 0 .273-.166.226-.328l-.23-.797c-.05-.177-.28-.177-.332 0Z");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.xiesyilgk {
  d: path("M19.654 7.404a.415.415 0 0 0 .036.815a34.158 34.158 0 0 1-.036-.815Z");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.y_jvuobbm {
  fill: var(--svg-color--605071, #605071);
  d: path("m12.504 13.39l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.ypwa00bgf {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m8.64 7.699l-.256.797c-.043.164.062.328.21.328h.318c.149 0 .254-.166.21-.328L8.907 7.7c-.046-.177-.218-.177-.266 0Z");
}

.yrn5k97fg {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.yrxal2b8w {
  stop-color: var(--svg-color--4c3735, #4C3735);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z78u0tbjp {
  fill: var(--svg-color--442a2e, #442A2E);
  d: path("m12.729 19.942l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-3.465-9.857Z");
}

.zdbmkmbsu {
  d: path("M8.787 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.ze3cmz88b {
  fill: var(--svg-color--202020, #202020);
  d: path("M20.38 6.584a1.203 1.203 0 0 1 .754-.156a.12.12 0 0 1-.029.24a.963.963 0 0 0-.634.143l-.007.006h-.001a.12.12 0 0 1-.147-.19l.064-.043Z");
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

.zur4xmb7i {
  d: path("M20.913 7.32a.387.387 0 0 0-.373.489h.748a.39.39 0 0 0-.375-.49Z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
