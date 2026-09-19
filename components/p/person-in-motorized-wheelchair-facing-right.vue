<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#io0PpPc)" transform="matrix(-1 0 0 1 12.877 6.958)" class="hxu4b4bgy"/><path fill="url(#iRmug6d)" transform="matrix(-1 0 0 1 12.877 6.958)" class="hxu4b4bgy"/><path class="pcgtfelps"/><path fill="url(#iVljtPy)" class="mt5vnnb7j"/><path fill="url(#ik5XPnb)" class="mt5vnnb7j"/><g filter="url(#iFnEFrb)"><path fill="url(#iw6YAFd)" class="gw9a35brn"/><path fill="url(#iAjG4Zb)" class="gw9a35brn"/><path fill="url(#i9qg56b)" class="gw9a35brn"/><path fill="url(#irVO1mb)" class="gw9a35brn"/></g><path class="wqt530bhs"/><path fill="url(#imVECvd)" class="ghvuf-blv"/><path fill="url(#inIG1xc)" class="ghvuf-blv"/><path fill="url(#iVyKvxc)" class="ghvuf-blv"/><path fill="url(#iNzR8ye)" transform="matrix(-1 0 0 1 17.076 15.124)" class="nm4erqbgo"/><path fill="url(#i4SA5Ie)" transform="matrix(-1 0 0 1 7.813 26.315)" class="citbmybyr"/><path fill="url(#ivd6tJb)" transform="matrix(-1 0 0 1 19.464 26.315)" class="citbmybyr"/><g filter="url(#iEteaOP)"><path clip-rule="evenodd" class="j8d535jif"/><path fill="url(#imNsfac)" clip-rule="evenodd" class="aojwa2yab"/></g><g filter="url(#iiiZY9d)"><path stroke="url(#iORSk6d)" class="mxzxi3l9a"/></g><circle fill="url(#iLK7nid)" transform="matrix(-1 0 0 1 17.582 15.915)" class="e8l0r5bvp"/><circle fill="url(#iRx1pQM)" transform="matrix(-1 0 0 1 17.582 15.915)" class="e8l0r5bvp"/><circle fill="url(#iKNNrbe)" transform="matrix(-1 0 0 1 17.582 15.915)" class="e8l0r5bvp"/><circle transform="matrix(-1 0 0 1 17.305 14.296)" class="b4att628q"/><circle fill="url(#igYiLkb)" transform="matrix(-1 0 0 1 17.305 14.296)" class="qhupv-mle"/><circle fill="url(#ir3vfRc)" transform="matrix(-1 0 0 1 17.305 14.296)" class="qhupv-mle"/><g filter="url(#iqMFSzc)"><path fill="url(#iYb5b6b)" class="u_guxfb1j"/><path fill="url(#iNCGSGv)" class="u_guxfb1j"/><path fill="url(#iIi6eZd)" class="u_guxfb1j"/></g><g filter="url(#irbbOhb)"><path class="v4t_fvbom"/><path fill="url(#i7cFVTb)" class="o9lqpnbkp"/></g><path class="id1-3t49a"/><path fill="url(#iG5Cp4k)" class="idurxibtj"/><path fill="url(#ix4Xtib)" class="idurxibtj"/><path fill="url(#iqmkn4d)" class="idurxibtj"/><path fill="url(#iDSbINb)" class="idurxibtj"/><path fill="url(#iANOQWc)" class="idurxibtj"/><rect fill="url(#iwPJDld)" transform="scale(-1 1)rotate(9.205 -45.303 -48.78)" class="z-j5q9xut"/><rect fill="url(#itmobse)" transform="scale(-1 1)rotate(9.205 -45.303 -48.78)" class="z-j5q9xut"/><path fill="url(#iDuZkMe)" transform="matrix(-1 0 0 1 15.818 20.749)" class="lgp2azslk"/><path fill="url(#irXs2md)" transform="matrix(-1 0 0 1 15.818 20.749)" class="lgp2azslk"/><g filter="url(#iSUqEJd)"><path class="ye09kufzl"/><path fill="url(#i00WQRc)" class="fu070pb0b"/><path fill="url(#iXU0GNb)" class="fu070pb0b"/></g><path fill="url(#ipUlx0c)" class="fu070pb0b"/><g filter="url(#iz35Myc)"><rect transform="matrix(-1 0 0 1 19.271 18.098)" class="n26ducxcj"/><rect fill="url(#iqljcRc)" transform="matrix(-1 0 0 1 19.271 18.098)" class="gwis82dft"/><rect fill="url(#iw4jA1t)" transform="matrix(-1 0 0 1 19.271 18.098)" class="gwis82dft"/></g><rect fill="url(#iiahDEe)" transform="matrix(-1 0 0 1 19.271 18.098)" class="gwis82dft"/><g filter="url(#i1yRsBd)"><path fill="url(#izDMLHb)" class="pnu4mab5b"/></g><path fill="url(#izUxldb)" class="pnu4mab5b"/><circle transform="matrix(-1 0 0 1 9.968 15.218)" class="m_-nxz25m"/><g filter="url(#ith6gLe)"><circle transform="matrix(-1 0 0 1 20.725 27.023)" class="t84n9rbqs"/></g><circle fill="url(#i0VqqEr)" transform="matrix(-1 0 0 1 20.725 27.023)" class="pyf4h2zzf"/><circle fill="url(#iPRFEMc)" transform="matrix(-1 0 0 1 20.122 27.625)" class="bwibo9t2c"/><circle fill="url(#iPRFEMc)" transform="matrix(-1 0 0 1 8.466 27.625)" class="bwibo9t2c"/><g filter="url(#iInLNdZ)"><path clip-rule="evenodd" class="uxl46hgfz"/></g><path fill="url(#i38WyRb)" clip-rule="evenodd" class="e5piu8b_x"/><g filter="url(#iXCdvac)"><circle transform="matrix(-1 0 0 1 19.605 28.142)" class="p2wklo0_t"/></g><g filter="url(#iThbOpb)"><circle transform="matrix(-1 0 0 1 7.949 28.142)" class="p2wklo0_t"/></g><g filter="url(#iauvFBq)"><path fill="url(#iB7Pogd)" class="ydu6asbhd"/></g><path fill="url(#iWXPinb)" class="ydu6asbhd"/><path fill="url(#iCAWc3c)" class="ydu6asbhd"/><circle fill="url(#iAfK1ib)" transform="matrix(-1 0 0 1 14.913 25.971)" class="o-elqripn"/><g filter="url(#i1PBRde)"><path clip-rule="evenodd" class="h-jpmbb2l"/></g><g filter="url(#ipYP9Le)"><path stroke="url(#ioD4PUk)" clip-rule="evenodd" class="q3gzl-bbb"/></g><g filter="url(#iGurTyd)"><path stroke="url(#iAsrsQe)" clip-rule="evenodd" class="glx3zzbnz"/></g><g filter="url(#ishPthg)"><path class="o130xfb5r"/></g><g filter="url(#ib3f6Ib)"><path stroke="url(#ipW2vPa)" clip-rule="evenodd" class="rwose_frq"/></g><g filter="url(#ivuPamd)"><circle transform="matrix(-1 0 0 1 14.038 26.846)" class="e2kdnzhzw"/></g><g filter="url(#ihxNFfb)"><path class="az-76qd6v"/></g><path fill="url(#ifElDie)" class="a_4fz-bmh"/><g filter="url(#izK1U7b)"><path class="p8x1e4bzh"/></g><g filter="url(#icP7wjb)"><path class="mrsorzbhw"/></g><path fill="url(#iGpWemb)" class="eebvkfb5w"/><g filter="url(#i7wH9ae)"><path fill="url(#ibLrPsa)" class="irfiz814c"/><path fill="url(#iJVLnbc)" class="irfiz814c"/></g><g filter="url(#io8zP1z)"><path class="wlt5jrb9d"/><path fill="url(#itXJQkd)" class="he_3oc6-r"/><path fill="url(#iA1xCic)" class="he_3oc6-r"/><path fill="url(#it1vG9b)" class="he_3oc6-r"/><path fill="url(#i3ZYd5d)" class="he_3oc6-r"/><path fill="url(#icqiEYc)" class="he_3oc6-r"/></g><path fill="url(#iPs41RU)" class="he_3oc6-r"/><path fill="url(#iQ6m6Oe)" class="he_3oc6-r"/><path fill="url(#iuWR2Gb)" class="bdi2omgsj"/><path clip-rule="evenodd" class="hwfcar-1c"/><g filter="url(#iafPvkd)"><path clip-rule="evenodd" class="zbqc9zbou"/></g><path class="bycx4bcet"/><path fill="url(#ic3ZzSd)" class="ynw1xcuzk"/><path fill="url(#ioL6k4i)" class="cpaufsb2j"/><ellipse fill="url(#iicaIud)" transform="scale(-1 1)rotate(31.039 -15.875 -22.055)" class="iap3byr6y"/><path class="fcfp0wlpn"/><path fill="url(#iOFlBud)" class="o5u7yva1r"/><path fill="url(#it1QuYb)" class="o5u7yva1r"/><path fill="url(#ii9yK7d)" class="o5u7yva1r"/><path fill="url(#i1sLCOB)" class="o5u7yva1r"/><path fill="url(#iFpDioe)" class="o5u7yva1r"/><g filter="url(#i1x0vrd)"><path fill="url(#i2MrH3d)" class="a478uubgd"/></g><path fill="url(#ikpjIbP)" class="pmekhkb2j"/><path fill="url(#iuVaXQJ)" class="pmekhkb2j"/><defs><radialGradient id="iVljtPy" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 4.75001 -5.30938 -5.16964 15.915 9.483)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="at42zcbhv"/><stop offset="1" class="pwpzq7byn"/></radialGradient><radialGradient id="iAjG4Zb" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 -1 2.95173 6.27243 19.852 21.796)" gradientUnits="userSpaceOnUse"><stop class="jzl720bvd"/><stop offset="1" class="zdh48sb9s"/></radialGradient><radialGradient id="i9qg56b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40625 6.4375 0 13.352 18.077)" gradientUnits="userSpaceOnUse"><stop class="d9q4mwzxt"/><stop offset="1" class="kegmapbvr"/></radialGradient><radialGradient id="irVO1mb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 .31251 -1.31893 -6.46254 22.634 19.671)" gradientUnits="userSpaceOnUse"><stop class="d0phtb81o"/><stop class="d0phtb81o"/><stop offset="1" class="hwvatcc-y"/></radialGradient><radialGradient id="imVECvd" cx="0" cy="0" r="1" gradientTransform="matrix(.11941 -1.8243 6.0381 .39524 23.634 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="ie8_agh2b"/><stop offset="1" class="gzc_qccoq"/></radialGradient><radialGradient id="iVyKvxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.01563 .00576 -.60488 25.93 23.718)" gradientUnits="userSpaceOnUse"><stop class="u9mcm6llv"/><stop offset="1" class="b-3vnvcpj"/></radialGradient><radialGradient id="imNsfac" cx="0" cy="0" r="1" gradientTransform="rotate(179.119 13.13 12.078)scale(1.01575 2.26584)" gradientUnits="userSpaceOnUse"><stop class="ihz8r9bpq"/><stop offset="1" class="cabiwub4i"/></radialGradient><radialGradient id="iLK7nid" cx="0" cy="0" r="1" gradientTransform="matrix(-.80087 -.53995 .5353 -.79397 1.17 .793)" gradientUnits="userSpaceOnUse"><stop class="id6hb3b7i"/><stop offset="1" class="nbyzmw_ck"/></radialGradient><radialGradient id="iRx1pQM" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 -.33594 .30415 .24757 1.076 .498)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="z1-difb5b"/><stop offset="1" class="yxnjz7r7g"/></radialGradient><radialGradient id="iKNNrbe" cx="0" cy="0" r="1" gradientTransform="matrix(.18962 -.81468 .57531 .1339 0 .944)" gradientUnits="userSpaceOnUse"><stop class="mcd03_b4y"/><stop offset="1" class="e14bc-vgp"/></radialGradient><radialGradient id="igYiLkb" cx="0" cy="0" r="1" gradientTransform="rotate(65.376 -.034 .67)scale(.41251)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="ipohnfkvg"/><stop offset="1" class="aur13kbnc"/></radialGradient><radialGradient id="ir3vfRc" cx="0" cy="0" r="1" gradientTransform="matrix(.41406 -.125 .14254 .47215 .05 .79)" gradientUnits="userSpaceOnUse"><stop class="clzavdftr"/><stop offset="1" class="w07b1tb5i"/></radialGradient><radialGradient id="iNCGSGv" cx="0" cy="0" r="1" gradientTransform="rotate(-158.199 13.01 10.952)scale(.75729 .97088)" gradientUnits="userSpaceOnUse"><stop class="b9iguid0k"/><stop offset="1" class="rfxr5lvvz"/></radialGradient><radialGradient id="itmobse" cx="0" cy="0" r="1" gradientTransform="rotate(-90.544 1.095 .493)scale(1.19329 .67738)" gradientUnits="userSpaceOnUse"><stop class="bcaxkqjfb"/><stop offset="1" class="kh4so6bgt"/></radialGradient><radialGradient id="iDuZkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16406 -2.98016 0 2.418 .11)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="yu1mih4mu"/><stop offset="1" class="eu5aevb0y"/></radialGradient><radialGradient id="irXs2md" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.36328 -3.72499 0 2.418 .637)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cvn34-xwu"/><stop offset=".771" class="i8rkxoa5u"/></radialGradient><radialGradient id="iXU0GNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.10465 .77326 -.66363 .94804 7.216 9.072)" gradientUnits="userSpaceOnUse"><stop class="t_w7gbbck"/><stop offset="1" class="pbwt4gb4m"/></radialGradient><radialGradient id="ipUlx0c" cx="0" cy="0" r="1" gradientTransform="matrix(.0138 .77326 -2.388 .04264 9.853 16.321)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="seor_02fd"/><stop offset="1" class="cfhwg-9zy"/></radialGradient><radialGradient id="izUxldb" cx="0" cy="0" r="1" gradientTransform="rotate(-179.274 7.515 7.744)scale(.64849 1.33813)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="etx6bbf-f"/><stop offset="1" class="xbtn5acgm"/></radialGradient><radialGradient id="i0VqqEr" cx="0" cy="0" r="1" gradientTransform="matrix(1.71874 -1.8125 1.7735 1.68175 .89 2.258)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iPRFEMc" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 1.676 -.079)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="i38WyRb" cx="0" cy="0" r="1" gradientTransform="rotate(-46.762 37.418 6.712)scale(2.87398 2.81213)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iCAWc3c" cx="0" cy="0" r="1" gradientTransform="matrix(.625 3.92187 -.8118 .12937 9.256 22.827)" gradientUnits="userSpaceOnUse"><stop class="th1brvxrz"/><stop offset="1" class="ux0of3-jj"/></radialGradient><radialGradient id="iAfK1ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -1.89062 2.41965 2.03971 1.11 2.121)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="iGpWemb" cx="0" cy="0" r="1" gradientTransform="matrix(-.36925 .92296 -1.17544 -.47026 14.827 5.286)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iJVLnbc" cx="0" cy="0" r="1" gradientTransform="matrix(.76203 -.12903 .1573 .92907 11.422 5.613)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="itXJQkd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93294 -1.56906 2.29302 -2.82479 11.129 6.966)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iA1xCic" cx="0" cy="0" r="1" gradientTransform="matrix(2.0225 .59182 -.83082 2.8393 9.474 3.782)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="it1vG9b" cx="0" cy="0" r="1" gradientTransform="matrix(.71443 -.29622 .13774 .33221 9.845 6.688)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="i3ZYd5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.66668 .1142 -.05273 .76953 10.819 2.38)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="icqiEYc" cx="0" cy="0" r="1" gradientTransform="rotate(130.389 6.266 4.111)scale(.63693 .91986)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iPs41RU" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -4.1852 6.41043 1.14876 9.54 7.419)" gradientUnits="userSpaceOnUse"><stop class="t4jg6lbel"/><stop offset="1" class="xd_rxccdu"/></radialGradient><radialGradient id="iQ6m6Oe" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 -.1875 .39767 4.37436 8.993 5.702)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="z6top7alb"/><stop offset="1" class="ebu-sjblb"/></radialGradient><radialGradient id="iuWR2Gb" cx="0" cy="0" r="1" gradientTransform="matrix(.50823 .80918 -1.31488 .82585 11.21 5.47)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ic3ZzSd" cx="0" cy="0" r="1" gradientTransform="rotate(173.563 6.636 3.1)scale(.24975 .48521)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ioL6k4i" cx="0" cy="0" r="1" gradientTransform="matrix(-.2269 .02557 -.05533 -.49103 13.73 5.44)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iOFlBud" cx="0" cy="0" r="1" gradientTransform="rotate(-100.964 7.17 -.92)scale(3.23851 1.02255)" gradientUnits="userSpaceOnUse"><stop class="fndizab4b"/><stop offset="1" class="hw8l16bxs"/></radialGradient><radialGradient id="i1sLCOB" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .875 -1.0205 1.3485 6.303 3.609)" gradientUnits="userSpaceOnUse"><stop class="v4yb5cu8i"/><stop offset="1" class="ewip82vxi"/></radialGradient><radialGradient id="iFpDioe" cx="0" cy="0" r="1" gradientTransform="rotate(97.765 2.889 4.944)scale(1.04079 3.79637)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="i00c46bgu"/><stop offset="1" class="gb6cd3sju"/></radialGradient><radialGradient id="iuVaXQJ" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 2.84801 -.63092 .07615 10.79 9.921)" gradientUnits="userSpaceOnUse"><stop class="a-xw_r42a"/><stop offset="1" class="vahp-bcdd"/></radialGradient><linearGradient id="io0PpPc" x1=".184" x2="1.501" y1="1.353" y2="1.236" gradientUnits="userSpaceOnUse"><stop class="dqw_0wbtq"/><stop offset="1" class="pg0gw1osm"/></linearGradient><linearGradient id="iRmug6d" x1="2.383" x2="1.227" y1="1.697" y2="1.759" gradientUnits="userSpaceOnUse"><stop class="gg7le5bub"/><stop offset="1" class="rtjr-xb4t"/></linearGradient><linearGradient id="ik5XPnb" x1="10.037" x2="14.446" y1="16.671" y2="12.108" gradientUnits="userSpaceOnUse"><stop class="t4k8t2b9t"/><stop offset="1" class="lhdv8ibog"/></linearGradient><linearGradient id="iw6YAFd" x1="14.04" x2="22.165" y1="16.827" y2="24.14" gradientUnits="userSpaceOnUse"><stop class="scqcqwblc"/><stop offset="1" class="j5-6p70xh"/></linearGradient><linearGradient id="inIG1xc" x1="21.688" x2="22.868" y1="25.304" y2="24.687" gradientUnits="userSpaceOnUse"><stop class="wjw662jrg"/><stop offset="1" class="xkzs54_ul"/></linearGradient><linearGradient id="iNzR8ye" x1="-.102" x2=".498" y1=".507" y2=".507" gradientUnits="userSpaceOnUse"><stop class="p8hc-w2ji"/><stop offset=".573" class="c76owwbvh"/></linearGradient><linearGradient id="i4SA5Ie" x1=".471" x2="0" y1=".684" y2=".34" gradientUnits="userSpaceOnUse"><stop offset=".323" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="ivd6tJb" x1=".052" x2=".513" y1=".676" y2=".426" gradientUnits="userSpaceOnUse"><stop offset=".385" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="iORSk6d" x1="25.748" x2="20.396" y1="24.171" y2="26.444" gradientUnits="userSpaceOnUse"><stop class="bq9mpqbzy"/><stop offset="1" class="ka6kobc6f"/></linearGradient><linearGradient id="iYb5b6b" x1="20.506" x2="17.849" y1="26.577" y2="24.671" gradientUnits="userSpaceOnUse"><stop class="f6z4yi_ag"/><stop offset="1" class="cu9n-vbgf"/></linearGradient><linearGradient id="iIi6eZd" x1="19.209" x2="19.037" y1="24.202" y2="24.671" gradientUnits="userSpaceOnUse"><stop class="ybejupycn"/><stop offset="1" class="o7v7nujms"/></linearGradient><linearGradient id="i7cFVTb" x1="7.224" x2="7.724" y1="24.171" y2="25.071" gradientUnits="userSpaceOnUse"><stop class="hlkhhwb3q"/><stop offset="1" class="b37qgpujw"/></linearGradient><linearGradient id="iG5Cp4k" x1="16.782" x2="16.782" y1="16.778" y2="17.438" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05dlfbsr"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="ix4Xtib" x1="18.056" x2="16.976" y1="17.891" y2="17.891" gradientUnits="userSpaceOnUse"><stop offset=".326" class="mykl6fbtk"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="iqmkn4d" x1="15.507" x2="16.325" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="jsdt5e8xl"/><stop offset="1" class="erpm-ebho"/></linearGradient><linearGradient id="iDSbINb" x1="15.507" x2="15.794" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="gxhbeh9zc"/><stop offset="1" class="t07ov5bcy"/></linearGradient><linearGradient id="iANOQWc" x1="18.056" x2="17.764" y1="17.84" y2="17.84" gradientUnits="userSpaceOnUse"><stop class="xs80ogben"/><stop offset="1" class="snka5sm3m"/></linearGradient><linearGradient id="iwPJDld" x1=".298" x2=".287" y1=".432" y2="1.637" gradientUnits="userSpaceOnUse"><stop class="ronnvab4v"/><stop offset="1" class="dt2-hrbth"/></linearGradient><linearGradient id="i00WQRc" x1="8.072" x2="9.784" y1="17.329" y2="17.164" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ejmms-frd"/><stop offset="1" class="bd5h7cqqn"/></linearGradient><linearGradient id="iqljcRc" x1="5.922" x2="5.922" y1=".23" y2="1.23" gradientUnits="userSpaceOnUse"><stop offset=".219" class="jqu95-b8t"/><stop offset="1" class="vt606lu7d"/></linearGradient><linearGradient id="iw4jA1t" x1="11.844" x2="10.547" y1="1.42" y2="1.42" gradientUnits="userSpaceOnUse"><stop class="e9_lu_tkl"/><stop offset="1" class="ms0rob30e"/></linearGradient><linearGradient id="iiahDEe" x1="0" x2=".516" y1="1.55" y2="1.55" gradientUnits="userSpaceOnUse"><stop offset=".255" class="aafld1b5m"/><stop offset="1" class="t9qy5zbtq"/></linearGradient><linearGradient id="izDMLHb" x1="11.435" x2="11.435" y1="15.017" y2="16.485" gradientUnits="userSpaceOnUse"><stop offset=".116" class="k8klmcqbt"/><stop offset="1" class="t8rqipb-o"/></linearGradient><linearGradient id="iB7Pogd" x1="13.412" x2="13.412" y1="21.905" y2="27.702" gradientUnits="userSpaceOnUse"><stop class="ebki_vbdj"/><stop offset=".752" class="w_fjow9gn"/></linearGradient><linearGradient id="iWXPinb" x1="17.756" x2="16.756" y1="25.546" y2="25.452" gradientUnits="userSpaceOnUse"><stop class="golah4bmm"/><stop offset="1" class="nhtvs4bus"/></linearGradient><linearGradient id="ioD4PUk" x1="11.795" x2="14.977" y1="25.711" y2="28.847" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iAsrsQe" x1="6.649" x2="8.447" y1="27.521" y2="29.293" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="ipW2vPa" x1="20.499" x2="19.015" y1="28.905" y2="27.468" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset="1" class="hxfvufi0i"/></linearGradient><linearGradient id="ifElDie" x1="17.446" x2="16.102" y1="13.692" y2="14.046" gradientUnits="userSpaceOnUse"><stop class="x37zrlbcp"/><stop offset="1" class="u2e3rxbtp"/></linearGradient><linearGradient id="ibLrPsa" x1="11.781" x2="14.4" y1="6.254" y2="6.118" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iicaIud" x1="-.006" x2=".164" y1=".045" y2=".101" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="it1QuYb" x1="6.428" x2="7.631" y1="6.015" y2="5.78" gradientUnits="userSpaceOnUse"><stop class="sputfhdoz"/><stop offset="1" class="x91xhsboa"/></linearGradient><linearGradient id="ii9yK7d" x1="8.193" x2="8.006" y1="7.102" y2="5.827" gradientUnits="userSpaceOnUse"><stop class="zeqefbvfd"/><stop offset="1" class="aetcf802l"/></linearGradient><linearGradient id="i2MrH3d" x1="21.977" x2="17.227" y1="23.046" y2="14.64" gradientUnits="userSpaceOnUse"><stop offset=".047" class="x9-imyafb"/><stop offset="1" class="uu4nvia_s"/></linearGradient><linearGradient id="ikpjIbP" x1="11.134" x2="11.634" y1="9.171" y2="12.452" gradientUnits="userSpaceOnUse"><stop class="hlxv8_5xa"/><stop offset="1" class="ulf1gwuyj"/></linearGradient><filter id="iFnEFrb" width="15.582" height="10.819" x="10.455" y="14.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.223529 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="iEteaOP" width="6.441" height="2.956" x="20.051" y="23.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="iiiZY9d" width="5.567" height="2.356" x="20.5" y="23.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4489" stdDeviation=".075"/></filter><filter id="iqMFSzc" width="4.441" height="3.418" x="16.701" y="23.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.109804 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="irbbOhb" width="4.535" height="3.468" x="5.658" y="23.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.145098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="iSUqEJd" width="4.718" height="10.273" x="7.076" y="8.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="iz35Myc" width="11.844" height="3.289" x="7.427" y="17.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.133333 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.184314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="i1yRsBd" width="7.15" height="1.822" x="7.935" y="14.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.137255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="ith6gLe" width="3.042" height="3.242" x="17.732" y="26.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="iInLNdZ" width="3.042" height="3.242" x="6.076" y="26.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="iXCdvac" width=".953" height=".953" x="18.752" y="28.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="iThbOpb" width=".953" height=".953" x="7.096" y="28.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="iauvFBq" width="9.072" height="5.925" x="8.876" y="21.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.0392157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="i1PBRde" width="5.213" height="5.612" x="10.869" y="24.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="ipYP9Le" width="4.858" height="4.858" x="10.871" y="24.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4489" stdDeviation=".125"/></filter><filter id="iGurTyd" width="2.743" height="2.742" x="6.129" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4489" stdDeviation=".075"/></filter><filter id="ishPthg" width="4.351" height="5.782" x="9.525" y="8.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4489" stdDeviation=".5"/></filter><filter id="ib3f6Ib" width="2.743" height="2.742" x="17.857" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4489" stdDeviation=".075"/></filter><filter id="ivuPamd" width="1.474" height="1.474" x="12.664" y="26.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4489" result="effect2_innerShadow_2_4489"/></filter><filter id="ihxNFfb" width="7.234" height="2.726" x="10.589" y="12.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.423529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="izK1U7b" width="1.984" height="1.537" x="16.401" y="13.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.647059 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="icP7wjb" width="1.948" height="1.321" x="15.95" y="13.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.541176 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="i7wH9ae" width="4.306" height="4.907" x="10.102" y="3.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.52549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="io8zP1z" width="4.99" height="5.384" x="9.076" y="1.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="iafPvkd" width=".915" height=".586" x="12.678" y="4.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4489"/></filter><filter id="i1x0vrd" width="5.063" height="8.469" x="17.759" y="15.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4489" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-motorized-wheelchair-facing-right" /></template>
<style>
.a_4fz-bmh {
  d: path("m12.534 12.936l-.062-.5a5.2 5.2 0 0 0-1.883.266c.01.164.05.597.125 1.016c.094.523.367 1.183 1.633 1.23c1.265.047 3.468-.152 3.726-.223c.206-.056.44-.065.532-.062l.968-.555c.195.07.375-.187.133-.39c-.325-.282-.98-.326-1.266-.313c-1.125-.387-3.073-.474-3.906-.469");
}

.a-xw_r42a {
  stop-color: var(--svg-color--e37f3a, #E37F3A);
}

.a478uubgd {
  d: path("m21.29 17.983l1.031 5.078l-.344.329l-1.718-5.875h-2V15.92l1.281.156c1.125.125 1.636 1.323 1.75 1.906");
}

.aafld1b5m {
  stop-color: var(--svg-color--64576e, #64576E);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.aetcf802l {
  stop-color: var(--svg-color--492f60, #492F60);
  stop-opacity: 0;
}

.ajt-21bdu {
  stop-color: var(--svg-color--3a183a, #3A183A);
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.aojwa2yab {
  fill-rule: evenodd;
  d: path("M26.303 23.857a.375.375 0 0 0-.502-.17l-3.788 1.864l-.01.003h-1.427a.375.375 0 0 0 0 .75h1.426a.8.8 0 0 0 .343-.08l3.787-1.865a.375.375 0 0 0 .17-.502");
}

.at42zcbhv {
  stop-color: var(--svg-color--e75c22, #E75C22);
  stop-opacity: 0;
}

.aur13kbnc {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
  stop-opacity: 0;
}

.az-76qd6v {
  fill: var(--svg-color--ffc136, #FFC136);
  d: path("m12.534 12.936l-.062-.5a5.2 5.2 0 0 0-1.883.266c.01.164.05.597.125 1.016c.094.523.367 1.183 1.633 1.23c1.265.047 3.468-.152 3.726-.223c.206-.056.44-.065.532-.062l.968-.555c.195.07.375-.187.133-.39c-.325-.282-.98-.326-1.266-.313c-1.125-.387-3.073-.474-3.906-.469");
}

.b-3vnvcpj {
  stop-color: var(--svg-color--565476, #565476);
  stop-opacity: 0;
}

.b37qgpujw {
  stop-color: var(--svg-color--f24147, #F24147);
  stop-opacity: 0;
}

.b3dj2bied {
  stop-color: var(--svg-color--c7b9d7, #C7B9D7);
}

.b4att628q {
  cx: 0.518px;
  cy: 0.518px;
  r: 0.518px;
  fill: var(--svg-color--4a2a60, #4A2A60);
}

.b9iguid0k {
  stop-color: var(--svg-color--cc3437, #CC3437);
}

.bcaxkqjfb {
  stop-color: var(--svg-color--404047, #404047);
}

.bd5h7cqqn {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
  stop-opacity: 0;
}

.bdi2omgsj {
  d: path("M11.842 6.266a.075.075 0 0 0 .061-.096l-.283-1.109c-.013-.054-.069-.087-.12-.064a.665.665 0 0 0 .342 1.269");
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bq9mpqbzy {
  stop-color: var(--svg-color--474652, #474652);
}

.bqaby2bzq {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
}

.bu0v-9rgl {
  stop-color: var(--svg-color--776287, #776287);
  stop-opacity: 0;
}

.bwibo9t2c {
  cx: 0.894px;
  cy: 0.894px;
  r: 0.894px;
}

.bycx4bcet {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.83 5.429l-.898.1c-.04-.355.128-.666.377-.694c.248-.028.481.238.521.594");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c76owwbvh {
  stop-color: var(--svg-color--393640, #393640);
}

.cabiwub4i {
  stop-color: var(--svg-color--535154, #535154);
  stop-opacity: 0;
}

.cfhwg-9zy {
  stop-color: var(--svg-color--422d5a, #422D5A);
  stop-opacity: 0;
}

.citbmybyr {
  d: path("M0 0h.471v1.492H0z");
}

.clzavdftr {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
}

.cpaufsb2j {
  d: path("m13.458 5.47l-.011-.065c-.019-.169.037-.313.125-.323s.175.118.194.287l.004.066z");
}

.cu9n-vbgf {
  stop-color: var(--svg-color--c7262d, #C7262D);
}

.cvn34-xwu {
  stop-color: var(--svg-color--832538, #832538);
  stop-opacity: 0;
}

.d0phtb81o {
  stop-color: var(--svg-color--9d969d, #9D969D);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.d9q4mwzxt {
  stop-color: var(--svg-color--5c5166, #5C5166);
}

.dqw_0wbtq {
  stop-color: var(--svg-color--ec972b, #EC972B);
}

.dt2-hrbth {
  stop-color: var(--svg-color--2b2731, #2B2731);
}

.e14bc-vgp {
  stop-color: var(--svg-color--ab556a, #AB556A);
  stop-opacity: 0;
}

.e2kdnzhzw {
  cx: 0.637px;
  cy: 0.637px;
  r: 0.637px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.e5piu8b_x {
  fill-rule: evenodd;
  d: path("M7.572 30.015a1.496 1.496 0 1 1 0-2.993a1.496 1.496 0 0 1 0 2.993m0-.603a.894.894 0 1 1 0-1.787a.894.894 0 0 1 0 1.787");
}

.e8l0r5bvp {
  cx: 0.794px;
  cy: 0.794px;
  r: 0.794px;
}

.e9_lu_tkl {
  stop-color: var(--svg-color--685977, #685977);
}

.ebki_vbdj {
  stop-color: var(--svg-color--e4355d, #E4355D);
}

.ebu-sjblb {
  stop-color: var(--svg-color--ea9c22, #EA9C22);
  stop-opacity: 0;
}

.eebvkfb5w {
  d: path("M14.511 5.508a.9.9 0 0 1-.28-.389l-.164.019l.115 1.022c.21.102.486.051.548-.144c.053-.168-.022-.361-.219-.508");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.ejmms-frd {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
}

.erpm-ebho {
  stop-color: var(--svg-color--64597c, #64597C);
  stop-opacity: 0;
}

.etx6bbf-f {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
}

.eu5aevb0y {
  stop-color: var(--svg-color--bb3143, #BB3143);
}

.ewip82vxi {
  stop-color: var(--svg-color--56426b, #56426B);
  stop-opacity: 0;
}

.f6z4yi_ag {
  stop-color: var(--svg-color--dd2f40, #DD2F40);
}

.fcfp0wlpn {
  fill: var(--svg-color--55426a, #55426A);
  d: path("M9.118 3.897a1.2 1.2 0 0 0-1.391-.972l-.565.1a1.2 1.2 0 0 0-.972 1.39l.3 1.696a1.2 1.2 0 0 0 1.39.972l.566-.1a1.2 1.2 0 0 0 .972-1.39z");
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fndizab4b {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
}

.ft5dv1b6b {
  fill: none;
}

.fu070pb0b {
  d: path("M10.04 9.296a1.4 1.4 0 0 0-1.382-1.172h-.182a1.4 1.4 0 0 0-1.38 1.628l1.378 8.346h3.02z");
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gb6cd3sju {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
  stop-opacity: 0;
}

.gg7le5bub {
  stop-color: var(--svg-color--976635, #976635);
}

.ghvuf-blv {
  d: path("M21.47 24.271c.196.485.388.943.567 1.346c1.097-.411 4-1.833 4-1.833c-.02-.163-.217-.526-.848-.677c-.63-.15-2.033-.131-2.655-.103c0-.006-.48.55-1.065 1.267");
}

.glx3zzbnz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.5 29.612a1.146 1.146 0 1 1 0-2.292a1.146 1.146 0 0 1 0 2.292Z");
}

.golah4bmm {
  stop-color: var(--svg-color--db4459, #DB4459);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gw9a35brn {
  d: path("m19.15 15.527l-3.914-.48l-4.53 3.426h8.582s1.636 4.634 2.75 7.144c1.096-.411 4-1.833 4-1.833c-.02-.163-.218-.526-.849-.677c-.63-.15-2.033-.131-2.655-.103c-.117-.825-.439-2.956-.788-4.882s-1.876-2.532-2.595-2.595");
}

.gwis82dft {
  width: 11.844px;
  height: 2.839px;
  rx: 0.5px;
}

.gxhbeh9zc {
  stop-color: var(--svg-color--483962, #483962);
}

.gzc_qccoq {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
}

.h-jpmbb2l {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M13.4 30.015a2.531 2.531 0 1 1 0-5.063a2.531 2.531 0 0 1 0 5.063m0-1.02a1.512 1.512 0 1 1 0-3.023a1.512 1.512 0 0 1 0 3.023");
}

.he_3oc6-r {
  d: path("M13.914 2.532c-.266-.418-.786-.467-1.037-.424c-.776.13-.852.412-1.575.346c-.764-.07-1.127.016-1.43.197l-.006.004c-.299.178-.917.548-.767 1.881c.138 1.228.65 1.828.887 2.036l-.04.02c-.201.099-.263.333-.163.535c.085.172.324.25.605.172c.322-.088.557-.16.741-.219a.23.23 0 0 0 .157-.242l-.114-1.011a.9.9 0 0 1 .347-.805c-.035-.442.077-.66.285-.79c.345-.218.468-.144 1.333-.295c.917-.16 1.109-.881.777-1.405");
}

.hlkhhwb3q {
  stop-color: var(--svg-color--f24147, #F24147);
}

.hlxv8_5xa {
  stop-color: var(--svg-color--e08018, #E08018);
}

.hw8l16bxs {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
  stop-opacity: 0;
}

.hwfcar-1c {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M13.267 6.517a.114.114 0 0 0 .02.16c.24.188.559.207.66.206a.114.114 0 0 0-.003-.228c-.086 0-.34-.019-.517-.158a.114.114 0 0 0-.16.02");
}

.hwvatcc-y {
  stop-color: var(--svg-color--9d969d, #9D969D);
  stop-opacity: 0;
}

.hxfvufi0i {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
  stop-opacity: 0;
}

.hxu4b4bgy {
  d: path("M0 0h1.914v2.752H0z");
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.i00c46bgu {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
}

.i8rkxoa5u {
  stop-color: var(--svg-color--832538, #832538);
}

.iap3byr6y {
  cx: 0.059px;
  cy: 0.08px;
  rx: 0.059px;
  ry: 0.08px;
}

.id1-3t49a {
  fill: var(--svg-color--5e4f7f, #5E4F7F);
  d: path("M18.056 17.278a.5.5 0 0 0-.5-.5h-1.549a.5.5 0 0 0-.5.5v.82h2.549z");
}

.id6hb3b7i {
  stop-color: var(--svg-color--b11943, #B11943);
}

.idurxibtj {
  d: path("M18.056 17.278a.5.5 0 0 0-.5-.5h-1.549a.5.5 0 0 0-.5.5v.82h2.549z");
}

.ie8_agh2b {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
  stop-opacity: 0;
}

.ihz8r9bpq {
  stop-color: var(--svg-color--535154, #535154);
}

.ipohnfkvg {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
}

.irfiz814c {
  d: path("M14.21 4.655c-.118-.724-.393-1.049-.516-1.139l-3.392.383l.267 2.881c1.005 1.84 3.418 1.652 3.699.914s.077-2.2-.059-3.039");
}

.j5-6p70xh {
  stop-color: var(--svg-color--908893, #908893);
}

.j8d535jif {
  fill: var(--svg-color--3b3349, #3B3349);
  fill-rule: evenodd;
  d: path("M26.303 23.857a.375.375 0 0 0-.502-.17l-3.788 1.864l-.01.003h-1.427a.375.375 0 0 0 0 .75h1.426a.8.8 0 0 0 .343-.08l3.787-1.865a.375.375 0 0 0 .17-.502");
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jqu95-b8t {
  stop-color: var(--svg-color--574568, #574568);
}

.jsdt5e8xl {
  stop-color: var(--svg-color--64597c, #64597C);
}

.jzl720bvd {
  stop-color: var(--svg-color--816d8d, #816D8D);
}

.k8klmcqbt {
  stop-color: var(--svg-color--645381, #645381);
}

.ka6kobc6f {
  stop-color: var(--svg-color--474652, #474652);
  stop-opacity: 0;
}

.kegmapbvr {
  stop-color: var(--svg-color--5c5166, #5C5166);
  stop-opacity: 0;
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.kh4so6bgt {
  stop-color: var(--svg-color--404047, #404047);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lgp2azslk {
  d: path("M0 0h4.836v1.273H0z");
}

.lhdv8ibog {
  stop-color: var(--svg-color--94161a, #94161A);
  stop-opacity: 0;
}

.lzxtmdbfr {
  stop-color: var(--svg-color--4a3a4c, #4A3A4C);
}

.m_-nxz25m {
  cx: 0.475px;
  cy: 0.475px;
  r: 0.475px;
  fill: var(--svg-color--3e3a4a, #3E3A4A);
}

.ma5b9zegf {
  stop-color: var(--svg-color--9c83b4, #9C83B4);
}

.mcd03_b4y {
  stop-color: var(--svg-color--ab556a, #AB556A);
}

.mrsorzbhw {
  fill: var(--svg-color--fbbf3c, #FBBF3C);
  d: path("M17.836 14.776c-.417-.495-.921-.668-1.13-.707c-.223-.062-.651-.075-.726.121a.43.43 0 0 0 .062.418a1.95 1.95 0 0 1 1.32.55a.32.32 0 0 0 .442.005a.284.284 0 0 0 .032-.387");
}

.ms0rob30e {
  stop-color: var(--svg-color--58426e, #58426E);
  stop-opacity: 0;
}

.mt5vnnb7j {
  d: path("m15.27 15.022l-3.792 3.118l-1.44-8.172c.196-1.362 1.875-1.576 2.518-1.507c.642.068 1.37.437 1.875 1.978c.405 1.234.728 3.57.84 4.583");
}

.mxzxi3l9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m25.842 24.023l-3.89 1.906h-1.227");
}

.mykl6fbtk {
  stop-color: var(--svg-color--564778, #564778);
}

.n26ducxcj {
  width: 11.844px;
  height: 2.839px;
  fill: var(--svg-color--58426f, #58426F);
  rx: 0.5px;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nbyzmw_ck {
  stop-color: var(--svg-color--b52f5e, #B52F5E);
}

.nhtvs4bus {
  stop-color: var(--svg-color--db4459, #DB4459);
  stop-opacity: 0;
}

.nm4erqbgo {
  d: path("M0 0h.578v1.285H0z");
}

.o-elqripn {
  cx: 1.512px;
  cy: 1.512px;
  r: 1.512px;
}

.o130xfb5r {
  fill: var(--svg-color--e44d1f, #E44D1F);
  d: path("m12.614 10.31l.262 2.525c-.687 0-1.69.102-2.07.172c-.074-.522-.232-1.725-.274-2.355c-.05-.788.17-1.098.424-1.268c.155-.103.596-.3 1.084 0c.39.24.545.717.574.925");
}

.o5u7yva1r {
  d: path("M9.118 3.897a1.2 1.2 0 0 0-1.391-.972l-.565.1a1.2 1.2 0 0 0-.972 1.39l.3 1.696a1.2 1.2 0 0 0 1.39.972l.566-.1a1.2 1.2 0 0 0 .972-1.39z");
}

.o7v7nujms {
  stop-color: var(--svg-color--b92c31, #B92C31);
  stop-opacity: 0;
}

.o9lqpnbkp {
  d: path("m6.08 25.156l3.059-1.72l1.054 3.269H6.48a.827.827 0 0 1-.399-1.549");
}

.p2wklo0_t {
  cx: 0.377px;
  cy: 0.377px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.p8hc-w2ji {
  stop-color: var(--svg-color--746e6d, #746E6D);
}

.p8x1e4bzh {
  fill: var(--svg-color--fbbf3c, #FBBF3C);
  d: path("M18.239 14.585c-.367-.533-.853-.754-1.057-.812c-.215-.083-.641-.137-.735.051a.43.43 0 0 0 .023.422c.643.083 1.02.403 1.261.675a.32.32 0 0 0 .44.047a.284.284 0 0 0 .068-.383");
}

.pbwt4gb4m {
  stop-color: var(--svg-color--675876, #675876);
  stop-opacity: 0;
}

.pcgtfelps {
  fill: var(--svg-color--ec7f2f, #EC7F2F);
  d: path("m15.27 15.022l-3.792 3.118l-1.44-8.172c.196-1.362 1.875-1.576 2.518-1.507c.642.068 1.37.437 1.875 1.978c.405 1.234.728 3.57.84 4.583");
}

.pg0gw1osm {
  stop-color: var(--svg-color--e39c2d, #E39C2D);
}

.pmekhkb2j {
  d: path("m12.334 10.071l.263 2.526c-.688 0-1.692.101-2.07.172c-.074-.522-.233-1.725-.274-2.355c-.052-.788.17-1.099.424-1.268c.154-.103.595-.3 1.083 0c.39.24.545.717.574.925");
}

.pnu4mab5b {
  d: path("M14.935 15.514a.7.7 0 0 0-.7-.7h-6.3l.274 1.671h6.026a.7.7 0 0 0 .7-.7z");
}

.pwpzq7byn {
  stop-color: var(--svg-color--e75c22, #E75C22);
}

.pyf4h2zzf {
  cx: 1.496px;
  cy: 1.496px;
  r: 1.496px;
}

.q3gzl-bbb {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.3 29.412a2.029 2.029 0 1 1 0-4.058a2.029 2.029 0 0 1 0 4.058Z");
}

.qhupv-mle {
  cx: 0.518px;
  cy: 0.518px;
  r: 0.518px;
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rfxr5lvvz {
  stop-color: var(--svg-color--cc3437, #CC3437);
  stop-opacity: 0;
}

.ronnvab4v {
  stop-color: var(--svg-color--211b2c, #211B2C);
}

.rtjr-xb4t {
  stop-color: var(--svg-color--c99223, #C99223);
  stop-opacity: 0;
}

.rwose_frq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.229 29.612a1.146 1.146 0 1 1 0-2.292a1.146 1.146 0 0 1 0 2.292Z");
}

.scqcqwblc {
  stop-color: var(--svg-color--7d7172, #7D7172);
}

.seor_02fd {
  stop-color: var(--svg-color--422d5a, #422D5A);
}

.snka5sm3m {
  stop-color: var(--svg-color--6b6080, #6B6080);
  stop-opacity: 0;
}

.sputfhdoz {
  stop-color: var(--svg-color--6a5c77, #6A5C77);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t_w7gbbck {
  stop-color: var(--svg-color--675876, #675876);
}

.t07ov5bcy {
  stop-color: var(--svg-color--483962, #483962);
  stop-opacity: 0;
}

.t4jg6lbel {
  stop-color: var(--svg-color--ed9721, #ED9721);
}

.t4k8t2b9t {
  stop-color: var(--svg-color--94161a, #94161A);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.t84n9rbqs {
  cx: 1.496px;
  cy: 1.496px;
  r: 1.496px;
  fill: var(--svg-color--857d8e, #857D8E);
}

.t8rqipb-o {
  stop-color: var(--svg-color--523579, #523579);
}

.t9qy5zbtq {
  stop-color: var(--svg-color--64576e, #64576E);
  stop-opacity: 0;
}

.th1brvxrz {
  stop-color: var(--svg-color--ed516c, #ED516C);
}

.u_guxfb1j {
  d: path("m20.72 25.156l-3.058-1.72l-.961 3.269h3.62a.827.827 0 0 0 .4-1.549");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u2e3rxbtp {
  stop-color: var(--svg-color--f3bc3a, #F3BC3A);
  stop-opacity: 0;
}

.u9mcm6llv {
  stop-color: var(--svg-color--565476, #565476);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uevlegbhj {
  stop-color: var(--svg-color--5b4874, #5B4874);
  stop-opacity: 0;
}

.ulf1gwuyj {
  stop-color: var(--svg-color--eb6425, #EB6425);
}

.uu4nvia_s {
  stop-color: var(--svg-color--958d9a, #958D9A);
  stop-opacity: 0;
}

.ux0of3-jj {
  stop-color: var(--svg-color--e2305a, #E2305A);
  stop-opacity: 0;
}

.uxl46hgfz {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M7.572 30.015a1.496 1.496 0 1 1 0-2.993a1.496 1.496 0 0 1 0 2.993m0-.603a.894.894 0 1 1 0-1.787a.894.894 0 0 1 0 1.787");
}

.v4t_fvbom {
  fill: var(--svg-color--f0303e, #F0303E);
  d: path("m6.08 25.156l3.059-1.72l1.054 3.269H6.48a.827.827 0 0 1-.399-1.549");
}

.v4yb5cu8i {
  stop-color: var(--svg-color--695b77, #695B77);
}

.vahp-bcdd {
  stop-color: var(--svg-color--e37f3a, #E37F3A);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vt606lu7d {
  stop-color: var(--svg-color--574568, #574568);
  stop-opacity: 0;
}

.w_fjow9gn {
  stop-color: var(--svg-color--d61f4c, #D61F4C);
}

.w07b1tb5i {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
  stop-opacity: 0;
}

.wjw662jrg {
  stop-color: var(--svg-color--321d4a, #321D4A);
}

.wlt5jrb9d {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M13.914 2.532c-.266-.418-.786-.467-1.037-.424c-.776.13-.852.412-1.575.346c-.764-.07-1.127.016-1.43.197l-.006.004c-.299.178-.917.548-.767 1.881c.138 1.228.65 1.828.887 2.036l-.04.02c-.201.099-.263.333-.163.535c.085.172.324.25.605.172c.322-.088.557-.16.741-.219a.23.23 0 0 0 .157-.242l-.114-1.011a.9.9 0 0 1 .347-.805c-.035-.442.077-.66.285-.79c.345-.218.468-.144 1.333-.295c.917-.16 1.109-.881.777-1.405");
}

.wqt530bhs {
  fill: var(--svg-color--4c477e, #4C477E);
  d: path("M21.47 24.271c.196.485.388.943.567 1.346c1.097-.411 4-1.833 4-1.833c-.02-.163-.217-.526-.848-.677c-.63-.15-2.033-.131-2.655-.103c0-.006-.48.55-1.065 1.267");
}

.x37zrlbcp {
  stop-color: var(--svg-color--f3bc3a, #F3BC3A);
}

.x9-imyafb {
  stop-color: var(--svg-color--958d9a, #958D9A);
}

.x91xhsboa {
  stop-color: var(--svg-color--55426a, #55426A);
  stop-opacity: 0;
}

.xbtn5acgm {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
  stop-opacity: 0;
}

.xd_rxccdu {
  stop-color: var(--svg-color--ed9721, #ED9721);
  stop-opacity: 0;
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xkzs54_ul {
  stop-color: var(--svg-color--4d487f, #4D487F);
  stop-opacity: 0;
}

.xs80ogben {
  stop-color: var(--svg-color--6b6080, #6B6080);
}

.y05dlfbsr {
  stop-color: var(--svg-color--5b4874, #5B4874);
}

.ybejupycn {
  stop-color: var(--svg-color--b92c31, #B92C31);
}

.ydu6asbhd {
  d: path("m17.514 26.654l.425-3.4a1.2 1.2 0 0 0-1.191-1.349h-6.672a1.2 1.2 0 0 0-1.191 1.343l.406 3.4a1 1 0 0 0 .993.882h6.237a1 1 0 0 0 .992-.876");
}

.ye09kufzl {
  fill: var(--svg-color--55416a, #55416A);
  d: path("M10.04 9.296a1.4 1.4 0 0 0-1.382-1.172h-.182a1.4 1.4 0 0 0-1.38 1.628l1.378 8.346h3.02z");
}

.ynw1xcuzk {
  d: path("M13.28 5.49v-.004c-.032-.29.066-.54.22-.558c.153-.017.304.205.337.495v.004z");
}

.yu1mih4mu {
  stop-color: var(--svg-color--9c1a55, #9C1A55);
}

.yxnjz7r7g {
  stop-color: var(--svg-color--c54169, #C54169);
  stop-opacity: 0;
}

.z-j5q9xut {
  width: 0.619px;
  height: 2.008px;
  rx: 0.31px;
}

.z1-difb5b {
  stop-color: var(--svg-color--c54169, #C54169);
}

.z6top7alb {
  stop-color: var(--svg-color--411d01, #411D01);
}

.zbqc9zbou {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M13.259 4.542a.7.7 0 0 1 .195-.036a.137.137 0 0 0 .003-.275a1 1 0 0 0-.282.05a.94.94 0 0 0-.353.2a.137.137 0 1 0 .186.2a.7.7 0 0 1 .25-.139");
}

.zdh48sb9s {
  stop-color: var(--svg-color--816d8d, #816D8D);
  stop-opacity: 0;
}

.zeqefbvfd {
  stop-color: var(--svg-color--321c43, #321C43);
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

</style>
