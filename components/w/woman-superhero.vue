<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHNqk0X)" class="e03oo9bvk"/><path fill="url(#imqjm9c)" class="e03oo9bvk"/><g filter="url(#ijO3fNe)"><path fill="url(#ia8zscL)" class="i9t6f2bxc"/></g><g filter="url(#io4BXcd)"><path fill="url(#ix4t9Os)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#iJ8i4Jd)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#iEdZCLc)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#iwAYUId)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#iqWs0fb)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#i33iaAe)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#i7Qm1sE)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#ikGzC7b)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#ialQWkb)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#ixpy7be)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#iXLXdAe)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#i0ctGpc)" clip-rule="evenodd" class="uyadchbra"/><path fill="url(#iierU7b)" clip-rule="evenodd" class="uyadchbra"/></g><path fill="url(#ivjsgxd)" class="jcl-2hb7f"/><path fill="url(#iod3k0b)" class="jcl-2hb7f"/><path class="hmnycxx5w"/><path fill="url(#iyhUdBG)" class="cllop4bqc"/><path fill="url(#iyeCLFd)" class="cllop4bqc"/><path fill="url(#i20rlAd)" class="cllop4bqc"/><path fill="url(#iRJv8Rc)" class="cu21d24az"/><path fill="url(#iyAgBob)" class="cu21d24az"/><path fill="url(#iLKBWPD)" class="cu21d24az"/><path fill="url(#i92uFDa)" class="cu21d24az"/><g filter="url(#iVp5sJd)"><path class="pbxi84b9i"/></g><g filter="url(#iYT2y4b)"><path fill="url(#i5XOWcD)" class="vm0vryi9k"/><path fill="url(#iIuGzte)" class="vm0vryi9k"/></g><path fill="url(#iRR6nWc)" class="vm0vryi9k"/><g filter="url(#iOUSHHc)"><ellipse class="ijlx-8buq"/></g><g filter="url(#ihoZ2pe)"><path fill="url(#ilz7GNd)" class="k7zk34bqa"/><path fill="url(#ioYHq8b)" class="k7zk34bqa"/><path fill="url(#ioWJHub)" class="k7zk34bqa"/></g><ellipse fill="url(#iKdWZUd)" class="skhx9acxb"/><ellipse fill="url(#iLpatmc)" class="skhx9acxb"/><rect fill="url(#ibFf2jb)" class="qhe9mm7xm"/><g filter="url(#imQOMOc)"><path fill="url(#iHroW6c)" class="wivhzzb1z"/></g><g filter="url(#iXOvelE)"><path fill="url(#ivGV0tb)" class="b33bjs2vo"/></g><g filter="url(#ilVzCJQ)"><path class="r_noxdbmb"/><path fill="url(#ijWkfqd)" class="wrf7i3ase"/></g><g filter="url(#irXWl9d)"><path class="zaljp6bdb"/><path fill="url(#i2bMPUb)" class="w13b5wbfy"/></g><g filter="url(#iYNIZ3T)"><path fill="url(#idYlUgB)" class="mhnfts14b"/><path fill="url(#iSzKh5i)" class="mhnfts14b"/><path fill="url(#ikDxyOc)" class="mhnfts14b"/><path fill="url(#iaTl8dc)" class="mhnfts14b"/><path fill="url(#iN3Y7Ld)" class="mhnfts14b"/><path fill="url(#i9yLhmc)" class="mhnfts14b"/><path fill="url(#irlBNub)" class="mhnfts14b"/></g><path fill="url(#ia62Kze)" class="mhnfts14b"/><g filter="url(#iYppxKb)"><path class="kjye3cb0a"/></g><path fill="url(#ivqUfbq)" class="e1tu763dm"/><path fill="url(#i9FGcte)" class="e1tu763dm"/><g filter="url(#i3p0jQd)"><path class="hc09a8bdp"/><path fill="url(#iZEt1ob)" class="flf92-bsi"/></g><g filter="url(#ivjch1b)"><path stroke="url(#iC6fiae)" class="ys4ax6bzk"/></g><path class="w1te-1b1u"/><g filter="url(#i9wF2dd)"><path class="lejkhab1t"/></g><g filter="url(#iSP5Sld)"><path class="lrajprm5a"/></g><path class="t7q_0hbld"/><path fill="url(#id2HEZb)" class="ol-rryc7f"/><path class="e364_qkiw"/><g filter="url(#ivCujEC)"><path class="ev10ybb8j"/><path fill="url(#iRYSsEd)" class="k1jle7b9w"/></g><g filter="url(#iKrAPmd)"><path fill="url(#iUahFWu)" class="huedjvbza"/></g><path class="kgesynbbi"/><path fill="url(#igloHrw)" class="o0glw0bjm"/><path class="vv0158bin"/><g filter="url(#idhMoHe)"><path fill="url(#iqIAZIe)" class="g2oabcbfu"/></g><g filter="url(#iaTpBuc)"><ellipse transform="rotate(-27.914 13.578 9.88)" class="p-y7gmb0x"/><ellipse fill="url(#iCiZLAe)" transform="rotate(-27.914 13.578 9.88)" class="fpx4fnbpu"/></g><g filter="url(#ijMNdEb)"><path fill="url(#irQD3sb)" class="tl97dgb8r"/><path fill="url(#i3Kptsc)" class="tl97dgb8r"/></g><g filter="url(#iUz4Rbb)"><path fill="url(#i17ijPc)" class="bvohfyw_b"/><path fill="url(#iUR4e0b)" class="bvohfyw_b"/><path fill="url(#iLcybbc)" class="bvohfyw_b"/></g><g filter="url(#i5ulV9b)"><path stroke="url(#ibjHWRa)" class="abmj8p52s"/></g><defs><radialGradient id="iHNqk0X" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5824 -20.8203 0 16 18.372)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="gawd5obvo"/><stop offset="1" class="rn540obxc"/></radialGradient><radialGradient id="imqjm9c" cx="0" cy="0" r="1" gradientTransform="rotate(124.924 1.228 11.052)scale(12.8824 12.131)" gradientUnits="userSpaceOnUse"><stop class="y9rlcreuk"/><stop offset="1" class="xd0kopb5v"/></radialGradient><radialGradient id="iJ8i4Jd" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -17.584 46.311)scale(3.18955 4.51784)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iEdZCLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.46 12.607)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iwAYUId" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.57099 -5.8032 0 16.031 12.7)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iqWs0fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.12 10.894)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="i33iaAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.712 8.457)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="i7Qm1sE" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.543 12.144)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="ikGzC7b" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.703 7.15)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="ialQWkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.54 9.722)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="ixpy7be" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.607 4.073)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iXLXdAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.326 5.905)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="i0ctGpc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.79437 -2.54347 2.53096 -3.77571 14.197 16.04)" gradientUnits="userSpaceOnUse"><stop class="tze5uybsa"/><stop offset="1" class="yl5h-ynza"/></radialGradient><radialGradient id="iierU7b" cx="0" cy="0" r="1" gradientTransform="rotate(-34.825 34.459 -20.551)scale(4.67296 4.64999)" gradientUnits="userSpaceOnUse"><stop class="tze5uybsa"/><stop offset="1" class="yl5h-ynza"/></radialGradient><radialGradient id="ivjsgxd" cx="0" cy="0" r="1" gradientTransform="rotate(123.174 5.837 15.598)scale(11.5365 12.2083)" gradientUnits="userSpaceOnUse"><stop class="r3949-bju"/><stop offset="1" class="s9sui_61e"/></radialGradient><radialGradient id="iod3k0b" cx="0" cy="0" r="1" gradientTransform="rotate(100.184 -.325 14.065)scale(5.30229 7.65346)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="t-ehpbubw"/><stop offset="1" class="h61yu9bmy"/></radialGradient><radialGradient id="iyeCLFd" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 0 0 14.5199 23.18 29.622)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="oj7ch-bkx"/><stop offset="1" class="ce13789qs"/></radialGradient><radialGradient id="i20rlAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.1762 .21924 0 23.68 29.955)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="x8ej_jb7y"/><stop offset="1" class="mjbwacbml"/></radialGradient><radialGradient id="iyAgBob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6875 0 0 -13.3438 9.555 29.779)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="wx3vdcbzg"/><stop offset="1" class="jug-l4bwb"/></radialGradient><radialGradient id="iLKBWPD" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 -1.5668 5.45335 .48945 5.71 29.955)" gradientUnits="userSpaceOnUse"><stop class="x_0jnxbib"/><stop offset="1" class="wn7157b9l"/></radialGradient><radialGradient id="i92uFDa" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 0 0 -15.1051 8.383 29.955)" gradientUnits="userSpaceOnUse"><stop class="ujtti6ofv"/><stop offset="1" class="gewmlvbcg"/></radialGradient><radialGradient id="iRR6nWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 .54687 -.67794 -.87163 19.711 23.404)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="l56m45bvi"/><stop offset="1" class="v2ucwt3jq"/></radialGradient><radialGradient id="ioYHq8b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8125 0 0 -3.66953 14.367 15.998)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="rqcot095h"/><stop offset="1" class="jbe42ccmq"/></radialGradient><radialGradient id="ioWJHub" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -3 0 20.742 15.341)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="mzeokobes"/><stop offset="1" class="qhzdg_bmj"/></radialGradient><radialGradient id="iKdWZUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.363 3.443 13.942)scale(1.76569 1.94865)" gradientUnits="userSpaceOnUse"><stop class="su-lx9b4e"/><stop offset="1" class="fh2jv1bsu"/></radialGradient><radialGradient id="iLpatmc" cx="0" cy="0" r="1" gradientTransform="rotate(111.306 1.436 15.466)scale(1.67712 2.10568)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="otqjsqgnm"/><stop offset="1" class="cz6js0bhr"/></radialGradient><radialGradient id="ibFf2jb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25001 1.79325 -2.57261 1.79328 15.711 16.903)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="x-h-knbrs"/><stop offset="1" class="vpyj3jbao"/></radialGradient><radialGradient id="ivGV0tb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.07 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="ijWkfqd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.51 -52.201)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="i2bMPUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.365 10.573)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="idYlUgB" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.344 7.09)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iSzKh5i" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.931 10.733)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="ikDxyOc" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.852 16.819)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iaTl8dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.77 9.552)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="m65i1_bok"/><stop offset=".963" class="eb1o2u7ko"/></radialGradient><radialGradient id="iN3Y7Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.659 11.692)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i9yLhmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.332 9.617)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="irlBNub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.113 9.704)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="ia62Kze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.127 11.105)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iZEt1ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.65808 -2.11298 .88634 -.27605 16.85 12.184)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="r37rgng3f"/><stop offset="1" class="cv-bsn7fp"/></radialGradient><radialGradient id="id2HEZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.213 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iRYSsEd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.456 .626)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igloHrw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.85 9.976)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iCiZLAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.563 10.195)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irQD3sb" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.805 4.947)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="i3Kptsc" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.92 4.196)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="i17ijPc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.823 2.448)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iUR4e0b" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.873 8.848)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iLcybbc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.18 9.333)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="ijO3fNe" width="25.813" height="14.219" x="3.094" y="15.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".125"/></filter><filter id="io4BXcd" width="15.268" height="15.268" x="8.522" y="1.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="iVp5sJd" width="9.1" height="7.705" x="10.989" y="22.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".5"/></filter><filter id="iYT2y4b" width="7.926" height="6.427" x="12.029" y="22.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.407843 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_923" result="effect2_innerShadow_4002_923"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_923" result="effect3_innerShadow_4002_923"/></filter><filter id="iOUSHHc" width="3.095" height="3.11" x="14.16" y="18.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".25"/></filter><filter id="ihoZ2pe" width="11.606" height="4.825" x="10.289" y="15.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="imQOMOc" width="3.318" height="3.218" x="9.737" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="iXOvelE" width="3.218" height="3.468" x="19.25" y="8.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="ilVzCJQ" width="3.148" height="3.148" x="19.284" y="8.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".25"/></filter><filter id="irXWl9d" width="2.648" height="2.648" x="10.041" y="9.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".125"/></filter><filter id="iYNIZ3T" width="10.191" height="11.027" x="10.936" y="5.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="iYppxKb" width="2.877" height="3.682" x="14.43" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".25"/></filter><filter id="i3p0jQd" width="2.03" height="2.671" x="15.119" y="10.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.615686 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="ivjch1b" width="3.702" height="1.526" x="14.18" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".05"/></filter><filter id="i9wF2dd" width="3.001" height="1.285" x="16.973" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="iSP5Sld" width="3.001" height="1.285" x="12.088" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_923"/></filter><filter id="ivCujEC" width=".786" height=".696" x="17.479" y="9.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".05"/></filter><filter id="iKrAPmd" width=".891" height=".913" x="18.319" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".1"/></filter><filter id="idhMoHe" width=".986" height="1.04" x="13.876" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".1"/></filter><filter id="iaTpBuc" width=".912" height=".704" x="13.121" y="9.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".05"/></filter><filter id="ijMNdEb" width="4.985" height="5.214" x="9.324" y="3.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".375"/></filter><filter id="iUz4Rbb" width="8.914" height="5.78" x="12.714" y="2.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".125"/></filter><filter id="i5ulV9b" width="1.145" height="2.31" x="12.84" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_923" stdDeviation=".125"/></filter><linearGradient id="ia8zscL" x1="16" x2="16" y1="16.236" y2="30.341" gradientUnits="userSpaceOnUse"><stop offset=".866" class="tyjpv6bnm"/><stop offset="1" class="xyu2htzlq"/></linearGradient><linearGradient id="ix4t9Os" x1="20.724" x2="13.483" y1="3.621" y2="17.063" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iyhUdBG" x1="26.992" x2="26.773" y1="30.247" y2="27.497" gradientUnits="userSpaceOnUse"><stop class="pmf-vsdxp"/><stop offset="1" class="w6_8my7ls"/></linearGradient><linearGradient id="iRJv8Rc" x1="8.586" x2="5.336" y1="25.154" y2="25.154" gradientUnits="userSpaceOnUse"><stop offset=".183" class="annwmpbcg"/><stop offset="1" class="l85-jsb-f"/></linearGradient><linearGradient id="i5XOWcD" x1="18.555" x2="13.805" y1="23.966" y2="27.31" gradientUnits="userSpaceOnUse"><stop class="big423byp"/><stop offset="1" class="zbo4__e4e"/></linearGradient><linearGradient id="iIuGzte" x1="15.992" x2="15.992" y1="22.857" y2="24.201" gradientUnits="userSpaceOnUse"><stop class="ash9yfbkf"/><stop offset="1" class="k-dn1jb7a"/></linearGradient><linearGradient id="ilz7GNd" x1="14.773" x2="20.117" y1="19.06" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="umjrh49bx"/><stop offset="1" class="d7r2s6row"/></linearGradient><linearGradient id="iHroW6c" x1="9.737" x2="12.696" y1="10.66" y2="10.66" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="ivqUfbq" x1="19.3" x2="12.477" y1="10.502" y2="10.502" gradientUnits="userSpaceOnUse"><stop class="panbxpb-d"/><stop offset="1" class="pd6yc7bcx"/></linearGradient><linearGradient id="i9FGcte" x1="10.88" x2="12.35" y1="10.377" y2="10.377" gradientUnits="userSpaceOnUse"><stop class="y889pj4rk"/><stop offset="1" class="x6pd8cx7r"/></linearGradient><linearGradient id="iC6fiae" x1="15.302" x2="15.755" y1="14.357" y2="13.485" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iUahFWu" x1="18.991" x2="18.677" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqIAZIe" x1="14.593" x2="14.279" y1="10.03" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibjHWRa" x1="13.14" x2="13.685" y1="4.375" y2="5.649" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-superhero" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abmj8p52s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.14 4.031c.023.243.235 1.157.545 1.71");
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.annwmpbcg {
  stop-color: var(--svg-color--3e80f0, #3E80F0);
}

.ash9yfbkf {
  stop-color: var(--svg-color--40a0f8, #40A0F8);
}

.b33bjs2vo {
  d: path("M20.859 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.big423byp {
  stop-color: var(--svg-color--47a1ff, #47A1FF);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bvohfyw_b {
  d: path("M15.428 2.783c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.275 6.537 2.984c1.572-.175 1.743.541 1.877.888c-.436-4.056-3.369-4.677-5.95-5.246");
}

.ce13789qs {
  stop-color: var(--svg-color--528adb, #528ADB);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cllop4bqc {
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cu21d24az {
  d: path("M8.383 18.468v11.487H4.039v-.036c.22-5.447 1.882-9.174 4.344-11.451");
}

.cv-bsn7fp {
  stop-color: var(--svg-color--ffe235, #FFE235);
  stop-opacity: 0;
}

.cz6js0bhr {
  stop-color: var(--svg-color--d79d4a, #D79D4A);
}

.d7r2s6row {
  stop-color: var(--svg-color--ff3656, #FF3656);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e03oo9bvk {
  d: path("M2.063 29.955c0-1.969.39-6.76 3.216-9.86C8.81 16.222 13.793 15.644 16 15.644s7.19.578 10.721 4.453c2.826 3.1 3.217 7.89 3.217 9.859z");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e1tu763dm {
  d: path("M10.956 9.31h-.012l.077 2.01h.315q.282 0 .534.12l.247.12c.09.04.178.08.267.11l.218.07c.425.13.88.14 1.306.02l.277-.08c.108-.03.217-.07.316-.12l.228-.11q.252-.12.534-.12h.346l.164-.668c.12-.39.265-.39.383 0l.094.668h.467q.282 0 .534.12l.208.1c.109.05.227.1.346.13l.307.09c.425.12.89.11 1.305-.04l.178-.06l.238-.09l.267-.12q.252-.12.534-.12h.394l.099-2.554l-.007-.106h-.387a1.55 1.55 0 0 1-.712-.24l-.05-.03a2.2 2.2 0 0 0-.554-.28c-.425-.15-.88-.16-1.305-.04l-.129.03c-.237.07-.465.17-.672.32s-.456.22-.713.22h-1.226c-.258 0-.505-.08-.713-.22l-.01-.01a2.3 2.3 0 0 0-.642-.31l-.09-.03c-.425-.12-.88-.12-1.305.02l-.04.01c-.207.07-.405.17-.593.29l-.03.03c-.217.14-.465.22-.722.22h-.288l-.003.08l.01.305z");
}

.e364_qkiw {
  fill: var(--svg-color--000, #000);
  d: path("M17.704 10.392a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.eb1o2u7ko {
  stop-color: var(--svg-color--d47c29, #D47C29);
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.ev10ybb8j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.688c.063.085-.07.189-.221.301c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.358c.15-.113.325-.136.388-.051");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fh2jv1bsu {
  stop-color: var(--svg-color--f2bb43, #F2BB43);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.flf92-bsi {
  d: path("m15.632 10.54l-.49 1.566c-.1.322.14.644.48.644h.725c.34 0 .58-.327.48-.645l-.49-1.566c-.105-.347-.595-.347-.705 0");
}

.fpx4fnbpu {
  cx: 13.578px;
  cy: 9.881px;
  rx: 0.389px;
  ry: 0.197px;
}

.ft5dv1b6b {
  fill: none;
}

.g2oabcbfu {
  d: path("M14.662 10.286c0-.288-.234-.48-.298-.538l-.288.279l.178.36z");
}

.gawd5obvo {
  stop-color: var(--svg-color--ff3b9a, #FF3B9A);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gewmlvbcg {
  stop-color: var(--svg-color--2154ca, #2154CA);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h61yu9bmy {
  stop-color: var(--svg-color--3a7ad3, #3A7AD3);
  stop-opacity: 0;
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hc09a8bdp {
  fill: var(--svg-color--ffc927, #FFC927);
  d: path("m15.632 10.54l-.49 1.566c-.1.322.14.644.48.644h.725c.34 0 .58-.327.48-.645l-.49-1.566c-.105-.347-.595-.347-.705 0");
}

.hmnycxx5w {
  fill: var(--svg-color--4e9eff, #4E9EFF);
  d: path("M23.68 18.468v11.487h4.343v-.036c-.22-5.447-1.881-9.174-4.343-11.451");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.huedjvbza {
  d: path("M19.01 10.274a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.i9t6f2bxc {
  d: path("M3.344 29.955c0-1.887.355-6.479 2.92-9.45c3.207-3.715 7.732-4.269 9.736-4.269s6.529.554 9.736 4.269c2.565 2.971 2.92 7.563 2.92 9.45z");
}

.ijlx-8buq {
  cx: 15.708px;
  cy: 20.263px;
  fill: var(--svg-color--2f62b7, #2F62B7);
  rx: 1.048px;
  ry: 1.055px;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.jbe42ccmq {
  stop-color: var(--svg-color--c31852, #C31852);
  stop-opacity: 0;
}

.jcl-2hb7f {
  d: path("M16.031 15.638c-6.228 0-11.584 4.188-11.992 14.281v.036h23.984v-.036c-.408-10.093-5.764-14.28-11.992-14.28");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jug-l4bwb {
  stop-color: var(--svg-color--407dbe, #407DBE);
}

.k-dn1jb7a {
  stop-color: var(--svg-color--4392f9, #4392F9);
  stop-opacity: 0;
}

.k1jle7b9w {
  d: path("M18.15 9.688c.063.085-.07.189-.221.301c-.151.113-.263.193-.327.108c-.063-.085.008-.246.159-.358c.15-.113.325-.136.388-.051");
}

.k7zk34bqa {
  d: path("m15.992 20.435l-5.04-3.023c-.323-.2-.663-.512-.663-.98c0-.497.585-.533.885-.544l4.818-.078l4.819.078c.3.01.884.047.884.543c0 .469-.34.781-.663.98z");
}

.kgesynbbi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.64 9.227c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.kjye3cb0a {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.639 10.35l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.l56m45bvi {
  stop-color: var(--svg-color--53b7ff, #53B7FF);
}

.l85-jsb-f {
  stop-color: var(--svg-color--3e77d8, #3E77D8);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lejkhab1t {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.173 10.004c.266-.467.67-.835 1.538-.835c.38 0 .747.105 1.072.368c.27.218.233.496.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrajprm5a {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.89 10.004c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.024.6l.555.317c.652-.21 1.373-.24 2.08-.45");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m65i1_bok {
  stop-color: var(--svg-color--ed933e, #ED933E);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mhnfts14b {
  d: path("M10.944 9.31h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02l.051-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.802-2.31 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

.mjbwacbml {
  stop-color: var(--svg-color--286adf, #286ADF);
  stop-opacity: 0;
}

.mzeokobes {
  stop-color: var(--svg-color--f04451, #F04451);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o0glw0bjm {
  d: path("M13.847 9.5a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj7ch-bkx {
  stop-color: var(--svg-color--528adb, #528ADB);
  stop-opacity: 0;
}

.ol-rryc7f {
  d: path("M18.215 9.5a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.otqjsqgnm {
  stop-color: var(--svg-color--f6c546, #F6C546);
  stop-opacity: 0;
}

.p-y7gmb0x {
  cx: 13.578px;
  cy: 9.881px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.panbxpb-d {
  stop-color: var(--svg-color--ff3291, #FF3291);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pbxi84b9i {
  fill: var(--svg-color--2f63d5, #2F63D5);
  d: path("M12.875 23.42a.885.885 0 0 0-.763 1.333l2.143 3.638a1.49 1.49 0 0 0 2.568 0l2.142-3.638a.885.885 0 0 0-.762-1.334z");
}

.pd6yc7bcx {
  stop-color: var(--svg-color--ff1f6f, #FF1F6F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmf-vsdxp {
  stop-color: var(--svg-color--4d87f8, #4D87F8);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qhe9mm7xm {
  width: 4.109px;
  height: 5.399px;
  x: 13.933px;
  y: 13.298px;
  rx: 2.055px;
}

.qhzdg_bmj {
  stop-color: var(--svg-color--f04451, #F04451);
  stop-opacity: 0;
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_noxdbmb {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.859 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r3949-bju {
  stop-color: var(--svg-color--4690e6, #4690E6);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rn540obxc {
  stop-color: var(--svg-color--ee344d, #EE344D);
}

.rqcot095h {
  stop-color: var(--svg-color--c31852, #C31852);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s9sui_61e {
  stop-color: var(--svg-color--3e75e1, #3E75E1);
}

.skhx9acxb {
  cx: 15.992px;
  cy: 20.17px;
  rx: 1.048px;
  ry: 1.055px;
}

.su-lx9b4e {
  stop-color: var(--svg-color--fff14e, #FFF14E);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t-ehpbubw {
  stop-color: var(--svg-color--3062ac, #3062AC);
}

.t7q_0hbld {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.422 9.227c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tl97dgb8r {
  d: path("M11.137 4.56c.621-.554 1.517-.56 2.02-.47l.402 1.29c-.257-.038-.486.051-.679.235c-.456 1.26-2.022 1.956-2.749 2.146c-.15-1.492-.067-2.246 1.006-3.202");
}

.tyjpv6bnm {
  stop-color: var(--svg-color--790b2c, #790B2C);
}

.tze5uybsa {
  stop-color: var(--svg-color--7d3d08, #7D3D08);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ujtti6ofv {
  stop-color: var(--svg-color--2154ca, #2154CA);
}

.umjrh49bx {
  stop-color: var(--svg-color--ce1f66, #CE1F66);
}

.uyadchbra {
  fill-rule: evenodd;
  d: path("M23.217 11.983a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455M10.957 9.31h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194c-.226.561-.656.99-1.19 1.235q-.024.008-.05.02l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v2ucwt3jq {
  stop-color: var(--svg-color--49a3ff, #49A3FF);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vm0vryi9k {
  d: path("M13.13 22.998a.95.95 0 0 0-.818 1.432l2.302 3.907a1.6 1.6 0 0 0 2.757 0l2.301-3.907a.95.95 0 0 0-.819-1.432z");
}

.vpyj3jbao {
  stop-color: var(--svg-color--ffbd35, #FFBD35);
}

.vv0158bin {
  fill: var(--svg-color--000, #000);
  d: path("M14.358 10.392a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.235");
}

.w13b5wbfy {
  d: path("M11.365 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.w1te-1b1u {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.031 13.661a3 3 0 0 1-1.421-.344c-.141-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w6_8my7ls {
  stop-color: var(--svg-color--4b99ff, #4B99FF);
  stop-opacity: 0;
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wivhzzb1z {
  d: path("M11.346 12.182a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.wn7157b9l {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
  stop-opacity: 0;
}

.wrf7i3ase {
  d: path("M20.859 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wx3vdcbzg {
  stop-color: var(--svg-color--407dbe, #407DBE);
  stop-opacity: 0;
}

.x_0jnxbib {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
}

.x-h-knbrs {
  stop-color: var(--svg-color--fd8645, #FD8645);
}

.x6pd8cx7r {
  stop-color: var(--svg-color--db5167, #DB5167);
  stop-opacity: 0;
}

.x8ej_jb7y {
  stop-color: var(--svg-color--286adf, #286ADF);
}

.xd0kopb5v {
  stop-color: var(--svg-color--bf2370, #BF2370);
  stop-opacity: 0;
}

.xyu2htzlq {
  stop-color: var(--svg-color--790b2c, #790B2C);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y889pj4rk {
  stop-color: var(--svg-color--db5167, #DB5167);
}

.y9rlcreuk {
  stop-color: var(--svg-color--bf2370, #BF2370);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yl5h-ynza {
  stop-color: var(--svg-color--d45b17, #D45B17);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.ys4ax6bzk {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.031 13.661a3 3 0 0 1-1.421-.344c-.141-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.zaljp6bdb {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.365 11.647a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.zbo4__e4e {
  stop-color: var(--svg-color--3f83f1, #3F83F1);
}

</style>
