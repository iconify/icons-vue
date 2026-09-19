<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#izLYjfC)"><path fill="url(#iNuhSbe)" class="tdiuq7fao"/><path fill="url(#idlFzTd)" class="tdiuq7fao"/><path fill="url(#ixC0due)" class="tdiuq7fao"/></g><path fill="url(#iHXygyL)" class="bpfn7eb2s"/><path fill="url(#iJ7Qllb)" class="bpfn7eb2s"/><path fill="url(#i7Mopzd)" class="loczt5alq"/><path fill="url(#i785HAb)" class="loczt5alq"/><path fill="url(#iPAkT5d)" class="b2of0-bbn"/><g filter="url(#iE3nsUN)"><circle fill="url(#iskp5Jd)" class="ngjau4blk"/></g><circle fill="url(#inzOlmb)" class="ngjau4blk"/><g filter="url(#i02MK8D)"><circle fill="url(#iZd7CCb)" class="ru3r_-9om"/><circle fill="url(#ihMX9He)" class="ru3r_-9om"/></g><circle fill="url(#ijrjIKD)" class="py6rcfcmg"/><circle fill="url(#i8nraPc)" class="py6rcfcmg"/><circle fill="url(#i9EnoBd)" class="py6rcfcmg"/><g filter="url(#iVo4Nnd)"><circle fill="url(#i0ojfoc)" class="l6sgmjbwc"/></g><g filter="url(#iEPDWxc)"><circle fill="url(#iKBZQQd)" class="zt6k5bb0g"/></g><g filter="url(#ivCrv6c)"><path fill="url(#iAI2Izb)" class="zhxtxmbse"/></g><path fill="url(#iKticmV)" class="zhxtxmbse"/><path fill="url(#ieLYLup)" class="zhxtxmbse"/><path fill="url(#imXsfLA)" class="zhxtxmbse"/><path fill="url(#ivmk1ze)" class="zhxtxmbse"/><path fill="url(#iZvQTJe)" class="zhxtxmbse"/><path fill="url(#iLMlTFb)" class="zhxtxmbse"/><path fill="url(#iBmCzHe)" class="zhxtxmbse"/><g filter="url(#i2HwDFe)"><path class="qncllkb-i"/><path fill="url(#iVOvvje)" class="a_hvhsbro"/></g><g filter="url(#iRUspId)"><path fill="url(#inhPcze)" class="b8mn7vckq"/><path fill="url(#iRLJ6hd)" class="b8mn7vckq"/><path fill="url(#ivuqjtb)" class="b8mn7vckq"/><path fill="url(#ixC1Lxd)" class="b8mn7vckq"/></g><g filter="url(#ivmJgeb)"><path fill="url(#iecPMAc)" class="fe1l0z7_m"/></g><g filter="url(#i2LRROc)"><path stroke="url(#iQs26Qd)" class="t5il5kboq"/></g><path class="gy0hnvbrf"/><path class="iqo8uemrf"/><path fill="url(#iHzIvPI)" class="nxkbw8-ip"/><path class="zw_1d78xs"/><g filter="url(#iiaH82d)"><path class="hjov0rz2v"/><path fill="url(#i5Y2ybp)" class="ut__vv23f"/></g><g filter="url(#iS9EDcc)"><path fill="url(#inYY5vc)" class="v604teblu"/></g><path class="g0ayeebpk"/><path fill="url(#iiTjgjc)" class="ca-430a-h"/><path class="rwdv29brg"/><g filter="url(#iolt4Uc)"><path fill="url(#ibSAdIc)" class="l-g8rzj3d"/></g><g filter="url(#iROf0ld)"><ellipse transform="rotate(-27.914 9.693 16.24)" class="jrzwe27ha"/><ellipse fill="url(#iVxx3ne)" transform="rotate(-27.914 9.693 16.24)" class="zc0r9ab2c"/></g><g filter="url(#i97cUae)"><path class="sk6s4zuap"/></g><g filter="url(#iVnPEOb)"><path class="id_qnfbpm"/></g><g filter="url(#i9vIEnM)"><path class="gvl0web-o"/></g><g filter="url(#iLUP5iU)"><path class="yaq20hbik"/></g><path clip-rule="evenodd" class="raauof54a"/><path clip-rule="evenodd" class="z-j30264o"/><g filter="url(#iq1AA7l)"><path class="by9l_ua0a"/></g><g filter="url(#iZREkBd)"><path class="dyirwabel"/><path fill="url(#inqMtAB)" class="uud65yb_v"/></g><g filter="url(#ijJ9hpR)"><ellipse transform="rotate(-72.126 19.363 10.181)" class="uhcqxv04y"/></g><g filter="url(#iJ6rE9c)"><ellipse transform="rotate(-112.601 17.634 9.881)" class="kg-ueebaq"/></g><g filter="url(#icpus5b)"><ellipse transform="rotate(-72.126 22.635 10.088)" class="sla914fnw"/></g><g filter="url(#ieD9PBb)"><path class="zgq-f3j1y"/></g><path fill="url(#i8e8Bqb)" class="vj644l90l"/><path fill="url(#iJWxzPi)" class="vj644l90l"/><path fill="url(#iKX1jHc)" class="vj644l90l"/><g filter="url(#iX4YWQq)"><circle fill="url(#iy7PmWc)" class="pv07bgvpr"/></g><g filter="url(#i6dj9kc)"><circle fill="url(#iN2QX3c)" class="veiy6vbhw"/></g><g filter="url(#iuFQ7cJ)"><ellipse fill="url(#isr41wd)" class="in_ejxggz"/></g><g filter="url(#iXqQvNe)"><ellipse fill="url(#iiPIWGb)" class="kbs2a1bkr"/></g><g filter="url(#inTOH2b)"><ellipse fill="url(#ixqAYze)" class="aiucn6boz"/></g><g filter="url(#iwcPDue)"><ellipse fill="url(#iUYiPAd)" class="fiucd6bxu"/></g><defs><radialGradient id="ixC0due" cx="0" cy="0" r="1" gradientTransform="matrix(2.33597 .56063 -1.01645 4.23521 24.544 20.348)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="u3c4-pefb"/><stop offset="1" class="fg65gcq3k"/></radialGradient><radialGradient id="iJ7Qllb" cx="0" cy="0" r="1" gradientTransform="matrix(-.72315 5.71875 -1.76612 -.22333 5.18 11.214)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="i03etdb1r"/><stop offset="1" class="g6ovblimk"/></radialGradient><radialGradient id="i7Mopzd" cx="0" cy="0" r="1" gradientTransform="rotate(114.582 6.064 18.677)scale(5.21979 3.23134)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="s035_7gmh"/><stop offset="1" class="u4-ajmbpe"/></radialGradient><radialGradient id="i785HAb" cx="0" cy="0" r="1" gradientTransform="matrix(.75 .64062 -.94586 1.10736 23.68 20.792)" gradientUnits="userSpaceOnUse"><stop class="ph1y4_owb"/><stop offset="1" class="tqrri-v1x"/></radialGradient><radialGradient id="iskp5Jd" cx="0" cy="0" r="1" gradientTransform="rotate(123.555 7.574 20.706)scale(4.08481 3.13169)" gradientUnits="userSpaceOnUse"><stop class="kinjo46ga"/><stop offset="1" class="qdylhtb9e"/></radialGradient><radialGradient id="inzOlmb" cx="0" cy="0" r="1" gradientTransform="rotate(147.508 11.163 17.42)scale(3.6858 3.92712)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="vc--wpv5i"/><stop offset="1" class="px38xp8bj"/></radialGradient><radialGradient id="iZd7CCb" cx="0" cy="0" r="1" gradientTransform="matrix(3.10645 3.0589 -4.2059 4.27127 3.18 16.808)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="ncvalo15m"/><stop offset="1" class="ypk86rbdc"/></radialGradient><radialGradient id="ihMX9He" cx="0" cy="0" r="1" gradientTransform="rotate(-131.319 7.367 9.285)scale(2.9382)" gradientUnits="userSpaceOnUse"><stop class="ukacpvb6i"/><stop offset="1" class="sduakebny"/></radialGradient><radialGradient id="ijrjIKD" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19529 3.12502 -2.71537 -2.77643 26.735 16.245)" gradientUnits="userSpaceOnUse"><stop class="dcu5mmz_e"/><stop offset="1" class="zevimfbjz"/></radialGradient><radialGradient id="i8nraPc" cx="0" cy="0" r="1" gradientTransform="rotate(86.579 3.072 21.134)scale(4.51635 3.15844)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="lixm3n6pq"/><stop offset="1" class="bht2cacxw"/></radialGradient><radialGradient id="i9EnoBd" cx="0" cy="0" r="1" gradientTransform="rotate(-49.927 30.587 -18.194)scale(2.57277 2.14992)" gradientUnits="userSpaceOnUse"><stop offset=".414" class="r1c8asbzu"/><stop offset="1" class="bmnxq0b1a"/></radialGradient><radialGradient id="iKBZQQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.76612 -2.22947 1.63407 1.29446 23.54 18.662)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="je0hzjbmv"/><stop offset=".822" class="wotxsdb-h"/></radialGradient><radialGradient id="iAI2Izb" cx="0" cy="0" r="1" gradientTransform="rotate(162.487 8.198 10.863)scale(10.8758 13.5362)" gradientUnits="userSpaceOnUse"><stop class="jbnrigbdy"/><stop offset="1" class="cj9l6wbnc"/></radialGradient><radialGradient id="iKticmV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96874 14.5937 -18.99167 -2.56204 16.756 15.804)" gradientUnits="userSpaceOnUse"><stop offset=".628" class="z5l-_tcvf"/><stop offset="1" class="euiclkb6d"/></radialGradient><radialGradient id="imXsfLA" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04764 -3.52884 0 18.183 17.168)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="b3obg0rjr"/><stop offset="1" class="x07k9zb7o"/></radialGradient><radialGradient id="ivmk1ze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.96512 3.20023 0 19.005 15.646)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="k3eazxbpm"/><stop offset="1" class="fu58w2bdz"/></radialGradient><radialGradient id="iZvQTJe" cx="0" cy="0" r="1" gradientTransform="rotate(-131.367 8.883 5.49)scale(3.11424 1.96834)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="rxgso0bpv"/><stop offset="1" class="tsw_tn6ix"/></radialGradient><radialGradient id="iLMlTFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.3272 -20.7746 0 14.49 16.692)" gradientUnits="userSpaceOnUse"><stop offset=".937" class="sulbs0bax"/><stop offset="1" class="fq_teth7g"/></radialGradient><radialGradient id="iBmCzHe" cx="0" cy="0" r="1" gradientTransform="matrix(4.62209 .39243 -.17507 2.06194 19.424 11.418)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="grg54_bye"/><stop offset="1" class="kfnq3-b5w"/></radialGradient><radialGradient id="ixC1Lxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50335 -.01294 .00394 -.45819 15.369 20.75)" gradientUnits="userSpaceOnUse"><stop class="fhepxlpmv"/><stop offset="1" class="xfo14fbgb"/></radialGradient><radialGradient id="iQs26Qd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 27.02 1.802)scale(1.36216 3.96394)" gradientUnits="userSpaceOnUse"><stop class="z0c7pub-j"/><stop offset="1" class="nxlcb4hsf"/></radialGradient><radialGradient id="iHzIvPI" cx="0" cy="0" r="1" gradientTransform="rotate(129.075 5.785 12.676)scale(2.35487 2.16245)" gradientUnits="userSpaceOnUse"><stop offset=".736" class="ul3qvdbsb"/><stop offset="1" class="mw2j5qblh"/></radialGradient><radialGradient id="i5Y2ybp" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.135 3.85)scale(.72514 .99835)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiTjgjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48444 1.82823 -1.67884 -1.36314 10.9 16.174)" gradientUnits="userSpaceOnUse"><stop offset=".736" class="ul3qvdbsb"/><stop offset="1" class="mw2j5qblh"/></radialGradient><radialGradient id="iVxx3ne" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.124 3.665)scale(.94791 1.13943)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inqMtAB" cx="0" cy="0" r="1" gradientTransform="matrix(-4.29639 0 0 -10.6161 25.57 12.902)" gradientUnits="userSpaceOnUse"><stop offset=".062" class="ytnm0cr0k"/><stop offset="1" class="akds29pjg"/></radialGradient><radialGradient id="i8e8Bqb" cx="0" cy="0" r="1" gradientTransform="rotate(156.024 12.873 6.54)scale(4.09526 2.31075)" gradientUnits="userSpaceOnUse"><stop offset=".291" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iJWxzPi" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14484 1.17874 -.7575 -1.37835 6.245 5.922)" gradientUnits="userSpaceOnUse"><stop class="cy3fw4bfy"/><stop offset="1" class="cw63m1bfl"/></radialGradient><radialGradient id="iy7PmWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.06452 0 0 -6.0729 5.954 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="tlnk369mx"/><stop offset="1" class="jccegnx7f"/></radialGradient><radialGradient id="iN2QX3c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.29064 0 0 -5.03764 9.499 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="hkvpugxoe"/><stop offset="1" class="ty3_ks7kr"/></radialGradient><radialGradient id="isr41wd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.583 0 0 -5.03764 14.058 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="ypx_bsb1m"/><stop offset=".911" class="frsmpkb3r"/></radialGradient><radialGradient id="iiPIWGb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12688 0 0 -4.26742 26.085 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="vc--wpv5i"/><stop offset="1" class="jccegnx7f"/></radialGradient><radialGradient id="ixqAYze" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50821 0 0 -4.78784 22.712 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="vc--wpv5i"/><stop offset=".699" class="hngzuob8m"/></radialGradient><radialGradient id="iUYiPAd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.60807 0 0 -3.43684 18.522 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="vc--wpv5i"/><stop offset=".912" class="k03m-pbsr"/></radialGradient><filter id="izLYjfC" width="25.147" height="24.814" x="4.246" y="1.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.0901961 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.384314 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24181" result="effect2_innerShadow_3987_24181"/></filter><filter id="iE3nsUN" width="5.05" height="4.95" x="25.187" y="24.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.47451 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/></filter><filter id="i02MK8D" width="6.491" height="6.391" x="2.063" y="14.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.466667 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/></filter><filter id="iVo4Nnd" width="4.777" height="4.777" x="2.87" y="15.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".2"/></filter><filter id="iEPDWxc" width="5.407" height="5.407" x="20.836" y="15.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".25"/></filter><filter id="ivCrv6c" width="20.606" height="23.675" x="4.686" y="6.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.454902 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/></filter><filter id="i2HwDFe" width="5.101" height="7.063" x="11.451" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="iRUspId" width="4.001" height="5.963" x="12.399" y="16.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".1"/></filter><filter id="ivmJgeb" width="4.001" height="5.963" x="12.399" y="15.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".1"/></filter><filter id="i2LRROc" width="6.574" height="2.458" x="11.112" y="22.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".05"/></filter><filter id="iiaH82d" width="1.325" height="1.151" x="17.268" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".05"/></filter><filter id="iS9EDcc" width="1.342" height="1.384" x="18.971" y="15.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".1"/></filter><filter id="iolt4Uc" width="1.524" height="1.627" x="10.449" y="15.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".1"/></filter><filter id="iROf0ld" width="1.568" height="1.168" x="8.909" y="15.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".05"/></filter><filter id="i97cUae" width="4.285" height="2.268" x="7.251" y="12.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/></filter><filter id="iVnPEOb" width="4.335" height="1.818" x="7.226" y="12.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".2"/></filter><filter id="i9vIEnM" width="4.27" height="2.293" x="17.278" y="12.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/></filter><filter id="iLUP5iU" width="4.32" height="1.843" x="17.203" y="12.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".2"/></filter><filter id="iq1AA7l" width="23.313" height="7.232" x="3.758" y="5.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".75"/></filter><filter id="iZREkBd" width="11.25" height="6.307" x="14.821" y="8.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.478431 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/></filter><filter id="ijJ9hpR" width="5.244" height="3.855" x="16.741" y="8.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="iJ6rE9c" width="4.681" height="3.572" x="15.294" y="8.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".25"/></filter><filter id="icpus5b" width="5.676" height="4.274" x="19.797" y="7.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="ieD9PBb" width="25.61" height="6.112" x="2.184" y="5.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.615686 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.564706 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24181" result="effect2_innerShadow_3987_24181"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.839216 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_24181" result="effect3_innerShadow_3987_24181"/></filter><filter id="iX4YWQq" width="4.79" height="4.79" x="2.389" y="6.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".25"/></filter><filter id="i6dj9kc" width="5.974" height="5.974" x="5.131" y="5.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="iuFQ7cJ" width="6.371" height="5.974" x="9.369" y="5.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="iXqQvNe" width="5.751" height="5.29" x="21.897" y="5.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="inTOH2b" width="6.27" height="5.752" x="18.106" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><filter id="iwcPDue" width="6.263" height="5.974" x="13.816" y="5.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24181" stdDeviation=".375"/></filter><linearGradient id="iNuhSbe" x1="17.148" x2="25.177" y1="1.868" y2="25.194" gradientUnits="userSpaceOnUse"><stop class="d8bevybne"/><stop offset="1" class="qp19kfbuy"/></linearGradient><linearGradient id="idlFzTd" x1="16.241" x2="16.241" y1="1.868" y2="4.714" gradientUnits="userSpaceOnUse"><stop class="om0t3ze-i"/><stop offset="1" class="c56mphbsh"/></linearGradient><linearGradient id="iHXygyL" x1="4.458" x2="4.458" y1="10.745" y2="16.761" gradientUnits="userSpaceOnUse"><stop class="u8devr01i"/><stop offset="1" class="p1fdemrcm"/></linearGradient><linearGradient id="iPAkT5d" x1="4.837" x2="5.493" y1="20.714" y2="24.87" gradientUnits="userSpaceOnUse"><stop class="g3wc7actq"/><stop offset="1" class="meb8p9b-o"/></linearGradient><linearGradient id="i0ojfoc" x1="5.462" x2="3.525" y1="17.495" y2="17.495" gradientUnits="userSpaceOnUse"><stop class="h2o6yw0uj"/><stop offset="1" class="umpo0x3lb"/></linearGradient><linearGradient id="ieLYLup" x1="24.292" x2="22.075" y1="21.646" y2="21.541" gradientUnits="userSpaceOnUse"><stop class="ol8lz5lrx"/><stop offset="1" class="s-2xfac7e"/></linearGradient><linearGradient id="iVOvvje" x1="14.319" x2="13.662" y1="22.044" y2="20.888" gradientUnits="userSpaceOnUse"><stop offset=".376" class="bl4qvs61j"/><stop offset="1" class="yef7rrb3h"/></linearGradient><linearGradient id="inhPcze" x1="14.4" x2="16.2" y1="19.772" y2="19.456" gradientUnits="userSpaceOnUse"><stop class="egj5oab6a"/><stop offset=".751" class="e0ys1otgd"/></linearGradient><linearGradient id="iRLJ6hd" x1="12.342" x2="14.402" y1="19.473" y2="19.587" gradientUnits="userSpaceOnUse"><stop class="ebvi3mb9l"/><stop offset="1" class="cdk9es-2l"/></linearGradient><linearGradient id="ivuqjtb" x1="14.399" x2="14.399" y1="20.304" y2="21.964" gradientUnits="userSpaceOnUse"><stop class="nt0_ohbdt"/><stop offset="1" class="jpx6f6ohm"/></linearGradient><linearGradient id="iecPMAc" x1="14.4" x2="14.4" y1="15.867" y2="18.262" gradientUnits="userSpaceOnUse"><stop class="flysjx3_r"/><stop offset="1" class="f8uqxcc7g"/></linearGradient><linearGradient id="inYY5vc" x1="20.077" x2="19.475" y1="16.527" y2="16.898" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibSAdIc" x1="11.64" x2="11.039" y1="16.527" y2="16.898" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKX1jHc" x1="17.837" x2="17.837" y1="14.464" y2="7.777" gradientUnits="userSpaceOnUse"><stop class="g1hnau62f"/><stop offset="1" class="wuvmmnb5o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mx-claus-medium" /></template>
<style>
.a_hvhsbro {
  d: path("m13.467 17.187l-1.218 3.526c-.208.726.291 1.45.999 1.45h1.508c.707 0 1.207-.736.999-1.45l-1.02-3.526c-.218-.782-1.04-.782-1.268 0");
}

.aiucn6boz {
  cx: 21.24px;
  cy: 8.478px;
  rx: 2.385px;
  ry: 2.126px;
}

.akds29pjg {
  stop-color: var(--svg-color--dfdde0, #DFDDE0);
  stop-opacity: 0;
}

.b2of0-bbn {
  d: path("M4.446 24.105c-.75-1.013-.796-3.12-.738-4.047h2.66v5.64c-.328-.109-1.172-.58-1.922-1.593");
}

.b3obg0rjr {
  stop-color: var(--svg-color--ca9f87, #CA9F87);
}

.b8mn7vckq {
  d: path("m13.666 16.811l-1.02 3.526c-.207.726.292 1.451 1 1.451h1.508c.707 0 1.207-.736.999-1.45l-1.02-3.527c-.218-.781-1.238-.781-1.467 0");
}

.bht2cacxw {
  stop-color: var(--svg-color--9e6a80, #9E6A80);
}

.bl4qvs61j {
  stop-color: var(--svg-color--915668, #915668);
}

.bmnxq0b1a {
  stop-color: var(--svg-color--c59b87, #C59B87);
  stop-opacity: 0;
}

.bpfn7eb2s {
  d: path("M4.727 13.042c-.075-1.237.529-2.237.774-2.57L3.415 9.323v7.438h1.562c-.052-.724-.175-2.481-.25-3.719");
}

.by9l_ua0a {
  fill: var(--svg-color--734853, #734853);
  d: path("M9.075 11.385a.69.69 0 0 0-.704 0c-.307.184-.664.29-1.045.29c-1.142 0-2.068-.948-2.068-2.117c0-1.168.926-2.116 2.068-2.116c.381 0 .738.106 1.045.29c.214.128.49.128.704 0a2.02 2.02 0 0 1 1.969-.067c.457.234 1.134.234 1.592 0a2.02 2.02 0 0 1 1.816-.016c.5.245 1.306.245 1.806 0a2.02 2.02 0 0 1 1.813.014c.464.237 1.16.237 1.624 0a2.02 2.02 0 0 1 1.997.087a.7.7 0 0 0 .735 0a2 2 0 0 1 1.076-.308c1.142 0 2.068.948 2.068 2.116s-.926 2.116-2.068 2.116c-.394 0-.762-.112-1.076-.308a.7.7 0 0 0-.735 0a2.02 2.02 0 0 1-1.997.087c-.464-.236-1.16-.236-1.624 0a2.02 2.02 0 0 1-1.813.015c-.5-.245-1.306-.245-1.806 0a2.02 2.02 0 0 1-1.816-.016c-.457-.234-1.135-.234-1.592 0a2.02 2.02 0 0 1-1.969-.067");
}

.c56mphbsh {
  stop-color: var(--svg-color--fe404f, #FE404F);
  stop-opacity: 0;
}

.ca-430a-h {
  d: path("M10.21 15.51a1.712 1.712 0 0 0-1.65 2.163h3.307c.039-.148.062-.296.062-.452a1.724 1.724 0 0 0-1.72-1.712");
}

.cdk9es-2l {
  stop-color: var(--svg-color--91695d, #91695D);
  stop-opacity: 0;
}

.cj9l6wbnc {
  stop-color: var(--svg-color--946965, #946965);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cw63m1bfl {
  stop-color: var(--svg-color--e5e1e2, #E5E1E2);
  stop-opacity: 0;
}

.cy3fw4bfy {
  stop-color: var(--svg-color--e5e1e2, #E5E1E2);
}

.d8bevybne {
  stop-color: var(--svg-color--fa3c46, #FA3C46);
}

.dcu5mmz_e {
  stop-color: var(--svg-color--c09a7c, #C09A7C);
}

.dyirwabel {
  fill: var(--svg-color--bdb3c4, #BDB3C4);
  d: path("M14.82 10.355c.173.625 1.026 1.9 3.063 2c1.184.058 2.08.059 2.801.06c.83 0 1.427 0 1.957.088c1.087.18 1.653.633 1.575 1.711q-.016.199-.028.41c.518.106.99.338 1.383.662V9.23H14.82z");
}

.e0ys1otgd {
  stop-color: var(--svg-color--cea491, #CEA491);
}

.ebvi3mb9l {
  stop-color: var(--svg-color--835c4f, #835C4F);
}

.egj5oab6a {
  stop-color: var(--svg-color--a2796a, #A2796A);
}

.euiclkb6d {
  stop-color: var(--svg-color--96557f, #96557F);
}

.f8uqxcc7g {
  stop-color: var(--svg-color--af8376, #AF8376);
  stop-opacity: 0;
}

.fe1l0z7_m {
  d: path("m13.666 16.453l-1.02 3.526c-.207.725.292 1.45 1 1.45h1.508c.707 0 1.207-.736.999-1.45l-1.02-3.526c-.218-.782-1.238-.782-1.467 0");
}

.fg65gcq3k {
  stop-color: var(--svg-color--9c2345, #9C2345);
  stop-opacity: 0;
}

.fhepxlpmv {
  stop-color: var(--svg-color--c69b8b, #C69B8B);
}

.fiucd6bxu {
  cx: 16.947px;
  cy: 8.478px;
  rx: 2.381px;
  ry: 2.237px;
}

.flysjx3_r {
  stop-color: var(--svg-color--af8376, #AF8376);
}

.fq_teth7g {
  stop-color: var(--svg-color--a36699, #A36699);
}

.frsmpkb3r {
  stop-color: var(--svg-color--bdbcbf, #BDBCBF);
}

.ft5dv1b6b {
  fill: none;
}

.fu58w2bdz {
  stop-color: var(--svg-color--b17f7c, #B17F7C);
  stop-opacity: 0;
}

.g0ayeebpk {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.813 14.988a2.68 2.68 0 0 0-2.599 2.031a.526.526 0 0 0 .514.654h4.28c.272 0 .49-.25.436-.522a2.69 2.69 0 0 0-2.63-2.163");
}

.g1hnau62f {
  stop-color: var(--svg-color--a88da8, #A88DA8);
}

.g3wc7actq {
  stop-color: var(--svg-color--b0acb0, #B0ACB0);
}

.g6ovblimk {
  stop-color: var(--svg-color--7c688b, #7C688B);
  stop-opacity: 0;
}

.grg54_bye {
  stop-color: var(--svg-color--7c4e5b, #7C4E5B);
}

.gvl0web-o {
  stroke: var(--svg-color--786488, #786488);
  stroke-linecap: round;
  d: path("M21.048 13.964c-.495-.364-1.754-1.023-3.27-.71");
}

.gy0hnvbrf {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M14.4 23.739a5.8 5.8 0 0 1-2.659-.63c-.262-.134-.545.162-.38.4a3.63 3.63 0 0 0 3.038 1.623a3.63 3.63 0 0 0 3.037-1.623c.166-.248-.116-.534-.38-.4a5.7 5.7 0 0 1-2.657.63");
}

.h2o6yw0uj {
  stop-color: var(--svg-color--6e494a, #6E494A);
}

.hjov0rz2v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.462 15.872c.122.163-.133.361-.423.578s-.504.369-.626.206s.014-.47.304-.687s.623-.26.745-.097");
}

.hkvpugxoe {
  stop-color: var(--svg-color--e5e1e9, #E5E1E9);
}

.hngzuob8m {
  stop-color: var(--svg-color--e2e1e3, #E2E1E3);
}

.i03etdb1r {
  stop-color: var(--svg-color--644d73, #644D73);
}

.id_qnfbpm {
  stroke: var(--svg-color--857b8d, #857B8D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.751 13.937c.495-.365 1.77-.996 3.285-.684");
}

.in_ejxggz {
  cx: 12.554px;
  cy: 8.478px;
  rx: 2.436px;
  ry: 2.237px;
}

.iqo8uemrf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.986 14.988a2.68 2.68 0 0 1 2.6 2.031a.526.526 0 0 1-.514.654h-4.28a.442.442 0 0 1-.436-.522a2.68 2.68 0 0 1 2.63-2.163");
}

.jbnrigbdy {
  stop-color: var(--svg-color--c89b86, #C89B86);
}

.jccegnx7f {
  stop-color: var(--svg-color--a8a4ad, #A8A4AD);
}

.je0hzjbmv {
  stop-color: var(--svg-color--b28775, #B28775);
}

.jpx6f6ohm {
  stop-color: var(--svg-color--975a71, #975A71);
}

.jrzwe27ha {
  cx: 9.693px;
  cy: 16.241px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.747px;
  ry: 0.378px;
}

.k03m-pbsr {
  stop-color: var(--svg-color--d4d3d5, #D4D3D5);
}

.k3eazxbpm {
  stop-color: var(--svg-color--b17f7c, #B17F7C);
}

.kbs2a1bkr {
  cx: 24.773px;
  cy: 8.478px;
  rx: 2.126px;
  ry: 1.895px;
}

.kfnq3-b5w {
  stop-color: var(--svg-color--7c4e5b, #7C4E5B);
  stop-opacity: 0;
}

.kg-ueebaq {
  cx: 17.634px;
  cy: 9.881px;
  fill: var(--svg-color--9889a1, #9889A1);
  rx: 1.136px;
  ry: 1.936px;
}

.kinjo46ga {
  stop-color: var(--svg-color--e0dce4, #E0DCE4);
}

.l-g8rzj3d {
  d: path("M11.773 17.02c0-.553-.45-.922-.57-1.033l-.554.534l.34.693z");
}

.l6sgmjbwc {
  cx: 5.258px;
  cy: 17.753px;
  r: 1.988px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lixm3n6pq {
  stop-color: var(--svg-color--af7d77, #AF7D77);
  stop-opacity: 0;
}

.loczt5alq {
  d: path("m22.632 25.68l.055-5.563l2.813-1.469c.125 1.01.162 3.513-.563 4.938s-1.846 1.979-2.305 2.094");
}

.meb8p9b-o {
  stop-color: var(--svg-color--a093ac, #A093AC);
}

.mw2j5qblh {
  stop-color: var(--svg-color--6a4a44, #6A4A44);
}

.ncvalo15m {
  stop-color: var(--svg-color--845d58, #845D58);
}

.ngjau4blk {
  cx: 27.562px;
  cy: 27.437px;
  r: 2.375px;
}

.nt0_ohbdt {
  stop-color: var(--svg-color--975a71, #975A71);
  stop-opacity: 0;
}

.nxkbw8-ip {
  d: path("M18.589 15.51a1.712 1.712 0 0 1 1.65 2.163H16.93a1.8 1.8 0 0 1-.062-.452c0-.941.77-1.712 1.72-1.712");
}

.nxlcb4hsf {
  stop-color: var(--svg-color--aa7f79, #AA7F79);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol8lz5lrx {
  stop-color: var(--svg-color--c0987f, #C0987F);
}

.om0t3ze-i {
  stop-color: var(--svg-color--e15157, #E15157);
}

.p1fdemrcm {
  stop-color: var(--svg-color--b1a6ab, #B1A6AB);
}

.ph1y4_owb {
  stop-color: var(--svg-color--afa9b2, #AFA9B2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pv07bgvpr {
  cx: 4.784px;
  cy: 8.478px;
  r: 1.895px;
}

.px38xp8bj {
  stop-color: var(--svg-color--dcd5e3, #DCD5E3);
  stop-opacity: 0;
}

.py6rcfcmg {
  cx: 23.54px;
  cy: 17.753px;
  r: 3.195px;
}

.qdylhtb9e {
  stop-color: var(--svg-color--cbbdcc, #CBBDCC);
}

.qncllkb-i {
  fill: var(--svg-color--86565c, #86565C);
  d: path("m13.467 17.187l-1.218 3.526c-.208.726.291 1.45.999 1.45h1.508c.707 0 1.207-.736.999-1.45l-1.02-3.526c-.218-.782-1.04-.782-1.268 0");
}

.qp19kfbuy {
  stop-color: var(--svg-color--e72d5f, #E72D5F);
}

.r1c8asbzu {
  stop-color: var(--svg-color--c59b87, #C59B87);
}

.raauof54a {
  fill: var(--svg-color--7f5b49, #7F5B49);
  fill-rule: evenodd;
  d: path("M11.758 18.304a.45.45 0 0 1 .028.636c-.814.889-1.96.966-2.433.966a.45.45 0 1 1 0-.9c.417 0 1.224-.079 1.77-.674a.45.45 0 0 1 .635-.028");
}

.ru3r_-9om {
  cx: 5.258px;
  cy: 17.753px;
  r: 3.195px;
}

.rwdv29brg {
  fill: var(--svg-color--000, #000);
  d: path("M11.19 17.221a.976.976 0 0 0-.98-.98a.976.976 0 0 0-.981.98c0 .164.039.32.109.452h1.735a1 1 0 0 0 .117-.452");
}

.rxgso0bpv {
  stop-color: var(--svg-color--916269, #916269);
}

.s-2xfac7e {
  stop-color: var(--svg-color--c89b84, #C89B84);
  stop-opacity: 0;
}

.s035_7gmh {
  stop-color: var(--svg-color--eae7ed, #EAE7ED);
}

.sduakebny {
  stop-color: var(--svg-color--814d60, #814D60);
  stop-opacity: 0;
}

.sk6s4zuap {
  stroke: var(--svg-color--786488, #786488);
  stroke-linecap: round;
  d: path("M7.751 13.937c.495-.365 1.77-.996 3.285-.684");
}

.sla914fnw {
  cx: 22.635px;
  cy: 10.088px;
  fill: var(--svg-color--9889a1, #9889A1);
  rx: 1.281px;
  ry: 2.154px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sulbs0bax {
  stop-color: var(--svg-color--995885, #995885);
  stop-opacity: 0;
}

.t5il5kboq {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.4 23.739a5.8 5.8 0 0 1-2.659-.63c-.262-.134-.545.162-.38.4a3.63 3.63 0 0 0 3.038 1.623a3.63 3.63 0 0 0 3.037-1.623c.166-.248-.116-.534-.38-.4a5.7 5.7 0 0 1-2.657.63Z");
}

.tdiuq7fao {
  d: path("M11.532 2.243c-4.09.332-5.594 2.35-6.616 4.013l-.17 1.958l14.979 1.742l3.52 6.39l3.107 9.948h2.54c-.273-3.375.037-12.195-.035-15.4c-.068-3.047-.965-5.434-3.655-7.505c-3.24-2.071-12.473-1.287-13.67-1.146");
}

.tlnk369mx {
  stop-color: var(--svg-color--cdc9d1, #CDC9D1);
}

.tqrri-v1x {
  stop-color: var(--svg-color--afa9b2, #AFA9B2);
  stop-opacity: 0;
}

.tsw_tn6ix {
  stop-color: var(--svg-color--916269, #916269);
  stop-opacity: 0;
}

.ty3_ks7kr {
  stop-color: var(--svg-color--a8a6aa, #A8A6AA);
}

.u3c4-pefb {
  stop-color: var(--svg-color--9c2345, #9C2345);
}

.u4-ajmbpe {
  stop-color: var(--svg-color--a294af, #A294AF);
}

.u8devr01i {
  stop-color: var(--svg-color--aca5af, #ACA5AF);
}

.uhcqxv04y {
  cx: 19.363px;
  cy: 10.181px;
  fill: var(--svg-color--9889a1, #9889A1);
  rx: 1.068px;
  ry: 1.936px;
}

.ukacpvb6i {
  stop-color: var(--svg-color--814d60, #814D60);
}

.ul3qvdbsb {
  stop-color: var(--svg-color--7e584b, #7E584B);
}

.umpo0x3lb {
  stop-color: var(--svg-color--784f53, #784F53);
}

.ut__vv23f {
  d: path("M18.462 15.872c.122.163-.133.361-.423.578s-.504.369-.626.206s.014-.47.304-.687s.623-.26.745-.097");
}

.uud65yb_v {
  d: path("M14.82 10.355c.173.625 1.026 1.9 3.063 2c1.184.058 2.08.059 2.801.06c.83 0 1.427 0 1.957.088c1.087.18 1.653.633 1.575 1.711q-.016.199-.028.41c.518.106.99.338 1.383.662V9.23H14.82z");
}

.v604teblu {
  d: path("M20.113 16.995a1.6 1.6 0 0 0-.443-.887l-.498.547l.224.437z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.veiy6vbhw {
  cx: 8.118px;
  cy: 8.478px;
  r: 2.237px;
}

.vj644l90l {
  d: path("M6.903 10.685a.87.87 0 0 0-.871 0a2.556 2.556 0 1 1 0-4.413a.87.87 0 0 0 .87 0c.38-.223.82-.35 1.292-.35c.41 0 .798.097 1.142.269c.565.283 1.403.283 1.968 0a2.55 2.55 0 0 1 1.142-.27c.395 0 .769.09 1.103.25c.618.296 1.615.296 2.233 0a2.55 2.55 0 0 1 2.24.018c.574.286 1.435.286 2.009 0a2.54 2.54 0 0 1 1.138-.267c.487 0 .942.136 1.33.373a.89.89 0 0 0 .909 0a2.556 2.556 0 1 1 0 4.367a.89.89 0 0 0-.91 0a2.54 2.54 0 0 1-1.329.372c-.409 0-.796-.096-1.138-.267c-.574-.285-1.435-.285-2.008 0a2.56 2.56 0 0 1-2.241.018c-.618-.296-1.615-.296-2.233 0a2.55 2.55 0 0 1-2.245-.02c-.565-.282-1.403-.282-1.968 0a2.55 2.55 0 0 1-1.142.27c-.471 0-.913-.128-1.291-.35");
}

.wotxsdb-h {
  stop-color: var(--svg-color--9f6a5d, #9F6A5D);
}

.wuvmmnb5o {
  stop-color: var(--svg-color--a88da8, #A88DA8);
  stop-opacity: 0;
}

.x07k9zb7o {
  stop-color: var(--svg-color--ca9f87, #CA9F87);
  stop-opacity: 0;
}

.xfo14fbgb {
  stop-color: var(--svg-color--c69b8b, #C69B8B);
  stop-opacity: 0;
}

.yaq20hbik {
  stroke: var(--svg-color--99969d, #99969D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.997 13.875c-.495-.365-1.754-1.024-3.27-.711");
}

.yef7rrb3h {
  stop-color: var(--svg-color--915668, #915668);
  stop-opacity: 0;
}

.ypk86rbdc {
  stop-color: var(--svg-color--744d4b, #744D4B);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.ytnm0cr0k {
  stop-color: var(--svg-color--dfdde0, #DFDDE0);
}

.z-j30264o {
  fill: var(--svg-color--916853, #916853);
  fill-rule: evenodd;
  d: path("M17.025 18.304a.45.45 0 0 0-.028.636c.814.889 1.96.966 2.434.966a.45.45 0 1 0 0-.9c-.418 0-1.225-.079-1.77-.674a.45.45 0 0 0-.636-.028");
}

.z0c7pub-j {
  stop-color: var(--svg-color--aa7f79, #AA7F79);
}

.z5l-_tcvf {
  stop-color: var(--svg-color--9c6573, #9C6573);
  stop-opacity: 0;
}

.zc0r9ab2c {
  cx: 9.693px;
  cy: 16.241px;
  rx: 0.747px;
  ry: 0.378px;
}

.zevimfbjz {
  stop-color: var(--svg-color--ac7c77, #AC7C77);
}

.zgq-f3j1y {
  fill: var(--svg-color--cdcccd, #CDCCCD);
  d: path("M6.903 10.685a.87.87 0 0 0-.871 0a2.556 2.556 0 1 1 0-4.413a.87.87 0 0 0 .87 0c.38-.223.82-.35 1.292-.35c.41 0 .798.097 1.142.269c.565.283 1.403.283 1.968 0a2.55 2.55 0 0 1 1.142-.27c.395 0 .769.09 1.103.25c.618.296 1.615.296 2.233 0a2.55 2.55 0 0 1 2.24.018c.574.286 1.435.286 2.009 0a2.54 2.54 0 0 1 1.138-.267c.487 0 .942.136 1.33.373a.89.89 0 0 0 .909 0a2.556 2.556 0 1 1 0 4.367a.89.89 0 0 0-.91 0a2.54 2.54 0 0 1-1.329.372c-.409 0-.796-.096-1.138-.267c-.574-.285-1.435-.285-2.008 0a2.56 2.56 0 0 1-2.241.018c-.618-.296-1.615-.296-2.233 0a2.55 2.55 0 0 1-2.245-.02c-.565-.282-1.403-.282-1.968 0a2.55 2.55 0 0 1-1.142.27c-.471 0-.913-.128-1.291-.35");
}

.zhxtxmbse {
  d: path("M5.143 23.486a7.51 7.51 0 0 0 7.454 6.534h3.62a7.51 7.51 0 0 0 7.453-6.534c.226-3.614.454-7.212.622-10.824c-.02-1.471-1.18-2.685-2.645-2.747H18.96a4.65 4.65 0 0 1-4.243-2.768a1.27 1.27 0 0 0-1.18-.802h-2.442c-3.54 0-6.41 2.901-6.41 6.482c0 3.569.223 7.08.457 10.659");
}

.zt6k5bb0g {
  cx: 23.54px;
  cy: 17.753px;
  r: 2.204px;
}

.zw_1d78xs {
  fill: var(--svg-color--000, #000);
  d: path("M17.608 17.221c0-.544.436-.98.98-.98c.546 0 .981.436.981.98c0 .164-.039.32-.109.452h-1.735a.9.9 0 0 1-.117-.452");
}

</style>
