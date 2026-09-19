<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3YIJAb)" transform="rotate(-27.486 8.001 6.573)" class="yv6n4cc_b"/><path fill="url(#iGAcVmc)" transform="rotate(-27.486 8.001 6.573)" class="yv6n4cc_b"/><path fill="url(#i4rzphe)" transform="rotate(-27.486 8.001 6.573)" class="yv6n4cc_b"/><path fill="url(#ito0rfb)" transform="rotate(-27.486 8.001 6.573)" class="yv6n4cc_b"/><path fill="url(#ijhvbUd)" transform="scale(-1 1)rotate(-27.486 1.145 53.553)" class="pnmas4b0d"/><path fill="url(#i4p5ckL)" transform="scale(-1 1)rotate(-27.486 1.145 53.553)" class="pnmas4b0d"/><path fill="url(#iMUFE5c)" transform="scale(-1 1)rotate(-27.486 1.145 53.553)" class="pnmas4b0d"/><path fill="url(#istcbVc)" transform="scale(-1 1)rotate(-27.486 1.145 53.553)" class="pnmas4b0d"/><g filter="url(#iroUSpb)"><path fill="url(#i01z4bb)" class="q06bipboe"/><path fill="url(#i4fdapb)" class="q06bipboe"/><path fill="url(#iuYGIBb)" class="q06bipboe"/><path fill="url(#iuL5pwb)" class="q06bipboe"/></g><g filter="url(#i4pWTIe)"><rect fill="url(#ijdYeId)" class="i5ifaebri"/><rect fill="url(#iUzNcCb)" class="i5ifaebri"/></g><g filter="url(#iapFl7c)"><path stroke="url(#iGMizue)" class="rk216mb_x"/></g><path fill="url(#iWNe2ya)" class="r1b-0re8u"/><path fill="url(#i6QhCId)" class="r1b-0re8u"/><path fill="url(#idVhk2c)" class="oh6h-kn8w"/><path fill="url(#iG9Zy0c)" class="oh6h-kn8w"/><path fill="url(#iNF5uQd)" class="qicne6b-o"/><path fill="url(#i5KMnoc)" class="qicne6b-o"/><path fill="url(#irUlh9d)" class="imjotkz7r"/><path fill="url(#ieWXbHe)" class="imjotkz7r"/><circle fill="url(#iOWbMXp)" class="ecvaggbgr"/><circle fill="url(#iDwDn9c)" class="ecvaggbgr"/><path fill="url(#imw8D0q)" class="w23km64va"/><path fill="url(#iqfy9Cd)" class="w23km64va"/><path fill="url(#iVZo1hd)" class="bqz6pj_ji"/><path fill="url(#ipD1fpc)" class="bqz6pj_ji"/><path fill="url(#ibkYewd)" class="q9xvks-dn"/><path fill="url(#i83nw2d)" class="q9xvks-dn"/><path fill="url(#iWQjHpA)" class="hnonm-gqr"/><path fill="url(#i0iJNke)" class="hnonm-gqr"/><circle fill="url(#idBwAKb)" transform="matrix(-1 0 0 1 21.67 6.722)" class="e4y-1lbum"/><circle fill="url(#icWCk4E)" transform="matrix(-1 0 0 1 21.67 6.722)" class="e4y-1lbum"/><g filter="url(#i2zsF8b)"><path fill="url(#ibWrmUb)" class="r54i5ibdm"/><path fill="url(#imcxYZd)" class="r54i5ibdm"/><path fill="url(#ivDbZ1b)" class="r54i5ibdm"/></g><g filter="url(#iVLgewc)"><path fill="url(#ioh2jQr)" class="lmpjyqbsr"/><path fill="url(#ibnnjId)" class="lmpjyqbsr"/><path fill="url(#iqeaRfc)" class="lmpjyqbsr"/></g><g filter="url(#iJhcxle)"><path fill="url(#idwoCcc)" class="ijt5wmo_r"/><path fill="url(#iJ7YPBd)" class="ijt5wmo_r"/></g><g filter="url(#ihYQoFc)"><path fill="url(#io8IDmc)" class="bu_b5db1f"/><path fill="url(#iZ7XSpb)" class="bu_b5db1f"/><path fill="url(#ibzLcCd)" class="bu_b5db1f"/></g><g filter="url(#iaeZb1h)"><path fill="url(#i6nY1Yc)" class="skr58ob4i"/><path fill="url(#ifV8kyc)" class="skr58ob4i"/></g><g filter="url(#iLjvHce)"><path fill="url(#iNoSEcS)" class="z_2l9eb3h"/></g><g filter="url(#i5GUoWb)"><path fill="url(#iihL6Fb)" class="zp8bw1b5w"/><path fill="url(#iINpxuc)" class="zp8bw1b5w"/></g><g filter="url(#iPu2YRd)"><path fill="url(#iErmypc)" class="tp6zg10cp"/></g><g filter="url(#iClnRvb)"><path fill="url(#iyI3B7c)" class="w8ndeybvy"/></g><g filter="url(#ic94fpc)"><path fill="url(#inVdEAf)" class="u_98my_vn"/><path fill="url(#icEA04J)" class="u_98my_vn"/></g><g filter="url(#iiuHebd)"><path fill="url(#iNZIlmc)" class="gab6v89yj"/></g><g filter="url(#i1BC6Hc)"><circle fill="url(#i0l5udb)" class="qhzn-0g9u"/></g><g filter="url(#ipLIwYc)"><circle fill="url(#iDDHUJe)" class="n0vrkdbqg"/></g><g filter="url(#iBzgupY)"><circle fill="url(#if0ugle)" class="neratzbwh"/><circle fill="url(#iOtUyYb)" class="neratzbwh"/></g><g filter="url(#iKF5U4F)"><circle class="copkocc0n"/><circle fill="url(#iyuUI0d)" class="vjrh0pbek"/><circle fill="url(#i0uXUad)" class="vjrh0pbek"/></g><g filter="url(#ijq6slc)"><path fill="url(#iMYIufc)" class="fyjvml9xy"/><path fill="url(#iGQZOve)" class="fyjvml9xy"/><path fill="url(#iQwyUfd)" class="fyjvml9xy"/><path fill="url(#iLU7agH)" class="fyjvml9xy"/><path fill="url(#ioGxSzb)" class="fyjvml9xy"/><path fill="url(#iMyEb7H)" class="fyjvml9xy"/></g><g filter="url(#ijQnBub)"><path fill="url(#iMzvdJd)" class="bkaq94b2d"/></g><g filter="url(#i8enmHb)"><path class="fo-6pbijy"/><path fill="url(#iSq5BJc)" class="klmyoyb5v"/><path fill="url(#iJU5DEc)" class="klmyoyb5v"/><path fill="url(#i8GuoDd)" class="klmyoyb5v"/><path fill="url(#igyrcec)" class="klmyoyb5v"/></g><g filter="url(#iNPVZJh)"><path class="rybwftbxz"/></g><g filter="url(#ibGG75d)"><path class="yqz616b0p"/><path fill="url(#ikca0Yc)" class="mxwwpcccp"/><path fill="url(#iTcdBXU)" class="mxwwpcccp"/><path fill="url(#iuBxkSb)" class="mxwwpcccp"/><path fill="url(#i7ubDDc)" class="mxwwpcccp"/></g><path class="yufx44vic"/><path class="e9_ydnoyv"/><path fill="url(#imRqMke)" class="kb_jmrbdz"/><path class="q9t1_2byy"/><g filter="url(#i0TlWPd)"><path class="gqo_xd8il"/><path fill="url(#iQg6Z6b)" class="igz2rpb-t"/></g><g filter="url(#iZM9Iyc)"><path fill="url(#ictDDob)" class="lh09d7e5c"/></g><path class="i70tdkkey"/><path fill="url(#ipgVBre)" class="nmv2-1blt"/><path class="vuyf4ac8d"/><g filter="url(#iT8I84b)"><path fill="url(#iAIusKg)" class="hvbh8zuzm"/></g><g filter="url(#inBbszd)"><ellipse transform="rotate(-27.914 15.001 12.66)" class="rsdtct9bb"/><ellipse fill="url(#i1QTHiG)" transform="rotate(-27.914 15.001 12.66)" class="am-ozkbdt"/></g><g filter="url(#imxr5tv)"><path class="grpvcqxuq"/></g><g filter="url(#ifheawe)"><path stroke="url(#i3tYLWb)" class="j6pr_v-ar"/></g><g filter="url(#iTQGDbe)"><path class="oaq7z0bnu"/></g><g filter="url(#i3GTRBc)"><path stroke="url(#iJlnotb)" class="m_-qq5luj"/></g><defs><radialGradient id="i3YIJAb" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.282 10.365)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="nfiy_hbvi"/><stop offset="1" class="m844pcc9l"/></radialGradient><radialGradient id="i4rzphe" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 10.453 7.05)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dms-h3b2e"/><stop offset="1" class="bx9frfb0m"/></radialGradient><radialGradient id="ito0rfb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.49 6.689)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="hwapycced"/><stop offset="1" class="g5p0-zbdt"/></radialGradient><radialGradient id="ijhvbUd" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.997 3.08)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="nfiy_hbvi"/><stop offset="1" class="m844pcc9l"/></radialGradient><radialGradient id="iMUFE5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 2.452 .476)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dms-h3b2e"/><stop offset="1" class="bx9frfb0m"/></radialGradient><radialGradient id="istcbVc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="hwapycced"/><stop offset="1" class="g5p0-zbdt"/></radialGradient><radialGradient id="i01z4bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.647 21.668)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="iuL5pwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 18.21 21.668)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="ijdYeId" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 18.053 5.417)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="iUzNcCb" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 9.233 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="iWNe2ya" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 4.131 2.94)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="i6QhCId" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.354 6.004)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="idVhk2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 9.135 5.597)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="iG9Zy0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 9.049 6.035)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="iNF5uQd" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.171 2.986)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="i5KMnoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.45 6.042)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="irUlh9d" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.828 2.982)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xmhbxgbvu"/><stop offset=".812" class="ve7x40mpw"/></radialGradient><radialGradient id="ieWXbHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.766 6.083)" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></radialGradient><radialGradient id="iOWbMXp" cx="0" cy="0" r="1" gradientTransform="rotate(134.624 4.151 5.642)scale(.6044)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="hcub0sbsp"/><stop offset=".91" class="c7vbstbpd"/></radialGradient><radialGradient id="iDwDn9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .21094 -.20725 -.17654 11.1 6.574)" gradientUnits="userSpaceOnUse"><stop class="f4u_rabzt"/><stop offset="1" class="kqaolnnzx"/></radialGradient><radialGradient id="imw8D0q" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.49 5.619)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="iqfy9Cd" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.457 10.305)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="iVZo1hd" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.814 5.597)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="ipD1fpc" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 10.056 10.339)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="ibkYewd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.395 5.617)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="i83nw2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.364 5.92)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="iWQjHpA" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 23.097 5.619)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="v_irgab5s"/><stop offset="1" class="kfj3unbwb"/></radialGradient><radialGradient id="i0iJNke" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 23.064 5.95)" gradientUnits="userSpaceOnUse"><stop class="a7a4ckbck"/><stop offset="1" class="n5n79mbfd"/></radialGradient><radialGradient id="idBwAKb" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="yv16imbst"/><stop offset=".91" class="hqci1tzzd"/></radialGradient><radialGradient id="icWCk4E" cx="0" cy="0" r="1" gradientTransform="matrix(-.06323 .28125 -.28686 -.0645 .462 .182)" gradientUnits="userSpaceOnUse"><stop class="t72jz0b3q"/><stop offset="1" class="ov1n1eber"/></radialGradient><radialGradient id="ibWrmUb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.584 18.48)" gradientUnits="userSpaceOnUse"><stop class="cnpza7b-j"/><stop offset="1" class="qcugcqlkb"/></radialGradient><radialGradient id="imcxYZd" cx="0" cy="0" r="1" gradientTransform="rotate(111.28 3.094 12.402)scale(2.73303 3.08168)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="my3wtvo7r"/><stop offset="1" class="yi8xsxb7e"/></radialGradient><radialGradient id="ivDbZ1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 20.097 20.978)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="xjez76bam"/><stop offset="1" class="fc_42m6ea"/></radialGradient><radialGradient id="ioh2jQr" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.772 6.21)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="idwoCcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.565 6.21)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="io8IDmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.346 6.21)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iZ7XSpb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 3.045 6.605)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i6nY1Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.71 6.21)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ifV8kyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.46 6.605)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iINpxuc" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.333 12.023)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iErmypc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.678 27.714)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="icEA04J" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.93 15.242)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iNZIlmc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.99 28.261)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="i0l5udb" cx="0" cy="0" r="1" gradientTransform="matrix(.84914 0 0 1.486 13.084 12.767)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iOtUyYb" cx="0" cy="0" r="1" gradientTransform="matrix(.40002 -.29128 .33246 .45657 18.675 12.639)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iyuUI0d" cx="0" cy="0" r="1" gradientTransform="matrix(.39739 -.73091 .4278 .2326 18.475 13.164)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="i0uXUad" cx="0" cy="0" r="1" gradientTransform="matrix(.12546 .12419 -.1601 .16174 18.495 12.767)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iGQZOve" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.56552 -6.19745 0 16.203 11.835)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="ioGxSzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.63247 .77842 0 17.324 12.152)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iMyEb7H" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.673 .83695 0 15.119 12.136)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iSq5BJc" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 16.183 -6.551)scale(1.48181 .5495)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iJU5DEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.85075 .17031 -.09158 .99514 17.497 9.928)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i8GuoDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81251 -1.25836 0 16.19 8.605)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="igyrcec" cx="0" cy="0" r="1" gradientTransform="matrix(1.48741 -1.09002 1.7077 2.33029 13.07 11.904)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i7ubDDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .09528 -.3061 0 16.348 13.688)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="imRqMke" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39249 -.6243 0 17.244 12.707)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iQg6Z6b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.688 2.178)scale(.183 .25195)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipgVBre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3925 -.62433 0 15.132 12.707)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1QTHiG" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.804 -.974)scale(.23905 .28735)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iroUSpb" width="9.5" height="4.284" x="11.444" y="21.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="i4pWTIe" width="27.875" height="1.225" x="2.334" y="5.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iapFl7c" width="27.781" height=".75" x="2.295" y="5.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".125"/></filter><filter id="i2zsF8b" width="10.708" height="10.353" x="11.075" y="11.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.490196 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iVLgewc" width="1.93" height="8.989" x="5.311" y="1.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iJhcxle" width="1.93" height="8.989" x="25.264" y="1.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="ihYQoFc" width="1.93" height="5.973" x="3.381" y="3.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iaeZb1h" width="1.93" height="5.973" x="27.194" y="3.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iLjvHce" width="3.719" height="6.065" x="9.162" y="22.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.690196 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.666667 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23322" result="effect2_innerShadow_3987_23322"/></filter><filter id="i5GUoWb" width="4.477" height="4.023" x="8.787" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iPu2YRd" width="4.833" height="2.114" x="7.311" y="27.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iClnRvb" width="3.719" height="5.564" x="20.194" y="22.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.658824 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23322" result="effect2_innerShadow_3987_23322"/></filter><filter id="ic94fpc" width="4.477" height="4.023" x="19.811" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iiuHebd" width="4.833" height="2.114" x="20.431" y="27.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="i1BC6Hc" width="1.816" height="1.616" x="13.084" y="11.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="ipLIwYc" width="1.963" height="1.963" x="12.911" y="11.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".25"/></filter><filter id="iBzgupY" width="1.866" height="1.866" x="17.688" y="11.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iKF5U4F" width="1.963" height="1.963" x="17.514" y="11.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".25"/></filter><filter id="ijq6slc" width="5.02" height="6.07" x="13.693" y="10.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="ijQnBub" width="4.055" height="3.484" x="15.271" y="9.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".5"/></filter><filter id="i8enmHb" width="6.098" height="4.042" x="13.141" y="8.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="iNPVZJh" width="2.352" height="2.797" x="14.898" y="11.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".375"/></filter><filter id="ibGG75d" width="1.108" height="1.497" x="15.635" y="12.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".05"/></filter><filter id="i0TlWPd" width=".384" height=".34" x="16.887" y="12.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".025"/></filter><filter id="iZM9Iyc" width=".338" height=".348" x="17.342" y="12.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".025"/></filter><filter id="iT8I84b" width=".384" height=".41" x="15.192" y="12.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".025"/></filter><filter id="inBbszd" width=".445" height=".344" x="14.779" y="12.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".025"/></filter><filter id="imxr5tv" width="1.559" height="1.154" x="14.353" y="11.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="ifheawe" width="1.372" height=".725" x="14.341" y="11.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".075"/></filter><filter id="iTQGDbe" width="1.559" height="1.154" x="16.744" y="11.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23322"/></filter><filter id="i3GTRBc" width="1.372" height=".725" x="16.692" y="11.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23322" stdDeviation=".075"/></filter><linearGradient id="iGAcVmc" x1="7.655" x2="9.18" y1="7.655" y2="8.008" gradientUnits="userSpaceOnUse"><stop offset=".136" class="b8cveibhx"/><stop offset="1" class="f6hdy7bzf"/></linearGradient><linearGradient id="i4p5ckL" x1="-.347" x2="1.178" y1="1.081" y2="1.434" gradientUnits="userSpaceOnUse"><stop offset=".136" class="b8cveibhx"/><stop offset="1" class="f6hdy7bzf"/></linearGradient><linearGradient id="i4fdapb" x1="20.584" x2="18.053" y1="24.98" y2="24.543" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="iuYGIBb" x1="11.897" x2="14.709" y1="25.074" y2="23.98" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="iGMizue" x1="2.67" x2="30.139" y1="7.128" y2="7.128" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="ibnnjId" x1="5.311" x2="6.803" y1="7.199" y2="7.199" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqeaRfc" x1="5.311" x2="5.584" y1="7.07" y2="7.07" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iJ7YPBd" x1="25.264" x2="26.459" y1="6.21" y2="6.21" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="ibzLcCd" x1="3.229" x2="3.723" y1="6.21" y2="6.21" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="iNoSEcS" x1="12.552" x2="9.754" y1="24.349" y2="24.349" gradientUnits="userSpaceOnUse"><stop offset=".335" class="m3819-b2y"/><stop offset="1" class="z0dt5e0_f"/></linearGradient><linearGradient id="iihL6Fb" x1="12.764" x2="8.787" y1="21.496" y2="21.496" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iyI3B7c" x1="23.958" x2="21.02" y1="24.928" y2="24.928" gradientUnits="userSpaceOnUse"><stop offset=".335" class="v4xj77b7s"/><stop offset="1" class="gjiuzgy3q"/></linearGradient><linearGradient id="inVdEAf" x1="19.811" x2="23.787" y1="21.496" y2="21.496" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iDDHUJe" x1="13.892" x2="13.582" y1="12.902" y2="12.902" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="if0ugle" x1="19.021" x2="18.625" y1="12.239" y2="13.466" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iMYIufc" x1="18.142" x2="14.447" y1="12.955" y2="13.506" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iQwyUfd" x1="13.459" x2="15.084" y1="13.694" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iLU7agH" x1="13.578" x2="14.489" y1="14.26" y2="14.227" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iMzvdJd" x1="15.932" x2="19.873" y1="11.511" y2="10.1" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="ikca0Yc" x1="15.771" x2="16.225" y1="13.418" y2="13.418" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iTcdBXU" x1="16.643" x2="16.147" y1="13.574" y2="13.567" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iuBxkSb" x1="16.284" x2="16.284" y1="13.934" y2="13.656" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="ictDDob" x1="17.62" x2="17.468" y1="12.733" y2="12.827" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAIusKg" x1="15.492" x2="15.34" y1="12.733" y2="12.827" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3tYLWb" x1="15.215" x2="14.827" y1="11.717" y2="11.228" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iJlnotb" x1="17.192" x2="17.579" y1="11.717" y2="11.228" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-lifting-weights-light" /></template>
<style>
.a7a4ckbck {
  stop-color: var(--svg-color--ebbeaf, #EBBEAF);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.am-ozkbdt {
  cx: 15.001px;
  cy: 12.661px;
  rx: 0.188px;
  ry: 0.095px;
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.b8cveibhx {
  stop-color: var(--svg-color--906466, #906466);
}

.bkaq94b2d {
  d: path("m18.107 10.045l-1.49.497a.507.507 0 0 0 .228.983l1.48-.198z");
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bqz6pj_ji {
  d: path("M24.095 5.35a.422.422 0 1 0-.843-.034v.585a.4.4 0 0 0 .798.03z");
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bu_b5db1f {
  d: path("M3.381 4.124a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bx9frfb0m {
  stop-color: var(--svg-color--c88f7e, #C88F7E);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c7vbstbpd {
  stop-color: var(--svg-color--d1998f, #D1998F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnpza7b-j {
  stop-color: var(--svg-color--4baeff, #4BAEFF);
}

.copkocc0n {
  cx: 18.495px;
  cy: 12.767px;
  r: 0.481px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dms-h3b2e {
  stop-color: var(--svg-color--a37073, #A37073);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4y-1lbum {
  r: 0.398px;
}

.e9_ydnoyv {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.345 12.345c.316 0 .582.218.655.512a.133.133 0 0 1-.13.165h-1.079a.11.11 0 0 1-.11-.132a.676.676 0 0 1 .664-.545");
}

.ecvaggbgr {
  cx: 10.858px;
  cy: 6.722px;
  r: 0.398px;
}

.f4u_rabzt {
  stop-color: var(--svg-color--fdd2c0, #FDD2C0);
}

.f6hdy7bzf {
  stop-color: var(--svg-color--c79990, #C79990);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fc_42m6ea {
  stop-color: var(--svg-color--3a9cef, #3A9CEF);
  stop-opacity: 0;
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.fo-6pbijy {
  fill: var(--svg-color--242324, #242324);
  d: path("m18.521 9.632l.208.104c.363.18.57.593.493 1.032l-.286 1.471c-.025.152-.125.254-.276.258h-.009s.026-.439.052-.697c.021-.21-.016-.273-.208-.464a.6.6 0 0 1-.181-.413v-.107a.28.28 0 0 0-.208-.258c-.312-.077-.96-.206-1.895-.206c-.934 0-1.583.129-1.894.206a.25.25 0 0 0-.208.258v.107c0 .155-.052.31-.182.413l-.078.077c-.104.078-.155.232-.155.361c.025.284.051.697.051.697h-.023a.31.31 0 0 1-.288-.258l-.285-1.47a.99.99 0 0 1 .519-1.007l.207-.104c.13-.077.26-.18.39-.283l.467-.49a.95.95 0 0 1 1.064-.156c.26.078.545.078.805 0c.389-.129.83-.025 1.142.259l.389.387c.104.129.233.206.39.283");
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fyjvml9xy {
  d: path("M13.693 11.775c0-.13.052-.284.156-.362l.078-.077a.51.51 0 0 0 .182-.413v-.413c0-.13.078-.232.207-.258c.312-.078.96-.207 1.895-.207c.934 0 1.583.13 1.895.207a.28.28 0 0 1 .207.258v.413c0 .155.078.31.182.413c.243.17.228.264.208.464c-.026.258-.052.697-.052.697h.009l-.13 1.915c-.077.857-.75 1.453-1.553 1.453h-1.553c-.828 0-1.476-.596-1.553-1.453c-.068-.879-.097-1.76-.178-2.638");
}

.g5p0-zbdt {
  stop-color: var(--svg-color--eeb8a1, #EEB8A1);
  stop-opacity: 0;
}

.gab6v89yj {
  d: path("M25.264 29.252v.376H20.63v-1.914h2.352c.383.377 1.215.73 1.836.942c.398.168.445.442.445.596");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gjiuzgy3q {
  stop-color: var(--svg-color--e9b4a6, #E9B4A6);
}

.gqo_xd8il {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.213 12.568c.03.04-.034.091-.107.146s-.127.093-.158.052c-.03-.041.004-.12.077-.174c.073-.055.157-.066.188-.024");
}

.grpvcqxuq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M14.562 11.455h.005l.008-.002l.021-.003l.07-.006a1.32 1.32 0 0 1 .896.29a.258.258 0 1 1-.317.408a.86.86 0 0 0-.55-.182l-.032.002l-.005.001a.258.258 0 0 1-.096-.508");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hcub0sbsp {
  stop-color: var(--svg-color--e8b7a2, #E8B7A2);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hnonm-gqr {
  d: path("M23.38 5.31a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.016z");
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hqci1tzzd {
  stop-color: var(--svg-color--ce978f, #CE978F);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.hvbh8zuzm {
  d: path("M15.526 12.857c0-.14-.114-.232-.144-.26l-.14.135l.086.175z");
}

.hwapycced {
  stop-color: var(--svg-color--d89c7f, #D89C7F);
}

.i5ifaebri {
  width: 27.875px;
  height: 1.025px;
  x: 2.334px;
  y: 5.697px;
  rx: 0.2px;
}

.i6vv_mv8s {
  stop-color: var(--svg-color--ffd6c1, #FFD6C1);
  stop-opacity: 0;
}

.i70tdkkey {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.031 12.345a.676.676 0 0 0-.655.512a.133.133 0 0 0 .13.165h1.079a.11.11 0 0 0 .11-.132a.68.68 0 0 0-.664-.545");
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.igz2rpb-t {
  d: path("M17.213 12.568c.03.04-.034.091-.107.146s-.127.093-.158.052c-.03-.041.004-.12.077-.174c.073-.055.157-.066.188-.024");
}

.ijt5wmo_r {
  d: path("M27.194 2.616a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.imjotkz7r {
  d: path("M9.147 5.31a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.822.016z");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j6pr_v-ar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.566 11.664c.207-.046.58-.009.923.258");
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.kb_jmrbdz {
  d: path("M17.245 12.476a.432.432 0 0 1 .416.546h-.834a.433.433 0 0 1 .418-.546");
}

.kfj3unbwb {
  stop-color: var(--svg-color--d19c91, #D19C91);
}

.klmyoyb5v {
  d: path("m18.521 9.632l.208.104c.363.18.57.593.493 1.032l-.286 1.471c-.025.152-.125.254-.276.258h-.009s.026-.439.052-.697c.021-.21-.016-.273-.208-.464a.6.6 0 0 1-.181-.413v-.107a.28.28 0 0 0-.208-.258c-.312-.077-.96-.206-1.895-.206c-.934 0-1.583.129-1.894.206a.25.25 0 0 0-.208.258v.107c0 .155-.052.31-.182.413l-.078.077c-.104.078-.155.232-.155.361c.025.284.051.697.051.697h-.023a.31.31 0 0 1-.288-.258l-.285-1.47a.99.99 0 0 1 .519-1.007l.207-.104c.13-.077.26-.18.39-.283l.467-.49a.95.95 0 0 1 1.064-.156c.26.078.545.078.805 0c.389-.129.83-.025 1.142.259l.389.387c.104.129.233.206.39.283");
}

.kqaolnnzx {
  stop-color: var(--svg-color--fdd2c0, #FDD2C0);
  stop-opacity: 0;
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lh09d7e5c {
  d: path("M17.63 12.851a.4.4 0 0 0-.113-.224l-.125.138l.056.11z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmpjyqbsr {
  d: path("M5.31 2.616a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_-qq5luj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.84 11.664c-.206-.046-.58-.009-.923.258");
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m3819-b2y {
  stop-color: var(--svg-color--ffd8c5, #FFD8C5);
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m844pcc9l {
  stop-color: var(--svg-color--dead9f, #DEAD9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mxwwpcccp {
  d: path("m16.005 12.773l-.258.822a.26.26 0 0 0 .252.339h.38a.262.262 0 0 0 .252-.339l-.257-.822c-.055-.182-.312-.182-.37 0");
}

.my3wtvo7r {
  stop-color: var(--svg-color--2161bb, #2161BB);
}

.n0vrkdbqg {
  cx: 13.892px;
  cy: 12.767px;
  r: 0.481px;
}

.n5n79mbfd {
  stop-color: var(--svg-color--ebbeaf, #EBBEAF);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.neratzbwh {
  cx: 18.495px;
  cy: 12.767px;
  r: 0.808px;
}

.nfiy_hbvi {
  stop-color: var(--svg-color--ffc8b2, #FFC8B2);
}

.nmv2-1blt {
  d: path("M15.132 12.476a.432.432 0 0 0-.417.546h.835a.435.435 0 0 0-.418-.546");
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.oaq7z0bnu {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M17.844 11.455h-.005l-.007-.002a1 1 0 0 0-.091-.01a1.37 1.37 0 0 0-.897.29a.258.258 0 1 0 .317.409a.86.86 0 0 1 .55-.182l.033.002l.004.001a.258.258 0 0 0 .096-.508");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh6h-kn8w {
  d: path("M8.432 5.35a.422.422 0 1 1 .844-.034v.585a.4.4 0 0 1-.799.03z");
}

.ov1n1eber {
  stop-color: var(--svg-color--e7bdaf, #E7BDAF);
  stop-opacity: 0;
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q06bipboe {
  d: path("M16.272 25.652c-2.363 0-4.203-.719-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q9t1_2byy {
  fill: var(--svg-color--000, #000);
  d: path("M16.998 12.908c0-.137.11-.247.247-.247a.246.246 0 0 1 .22.36h-.438a.2.2 0 0 1-.03-.113");
}

.q9xvks-dn {
  d: path("M22.663 5.348a.401.401 0 1 0-.802-.014v.575a.391.391 0 0 0 .783.013z");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qcugcqlkb {
  stop-color: var(--svg-color--2e82d2, #2E82D2);
}

.qhzn-0g9u {
  cx: 13.892px;
  cy: 12.767px;
  r: 0.808px;
}

.qicne6b-o {
  d: path("M9.864 5.348a.401.401 0 1 1 .802-.014v.575a.391.391 0 0 1-.782.013z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1b-0re8u {
  d: path("M7.773 5.431a.399.399 0 1 1 .796-.033v.46a.38.38 0 0 1-.758.032z");
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r54i5ibdm {
  d: path("m11.22 12.748l2.396-1.12l2.578 3.399l2.468-3.563l2.73 1.318a.25.25 0 0 1 .113.34l-1.194 2.304a1 1 0 0 0-.112.48l.12 5.762h-7.985V15.88a1 1 0 0 0-.098-.433L11.1 13.083a.25.25 0 0 1 .12-.335");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rk216mb_x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.67 6.128h27.031");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rsdtct9bb {
  cx: 15.001px;
  cy: 12.661px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.188px;
  ry: 0.095px;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rybwftbxz {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m16.056 12.852l-.397.822c-.049.17.07.338.236.338h.357c.167 0 .286-.171.236-.338l-.24-.822c-.053-.182-.138-.182-.192 0");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.skr58ob4i {
  d: path("M29.123 4.124a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t72jz0b3q {
  stop-color: var(--svg-color--e7bdaf, #E7BDAF);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tp6zg10cp {
  d: path("M7.31 29.252v.376h4.634v-1.914H9.592c-.383.377-1.215.73-1.836.942c-.398.168-.445.442-.445.596");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.u_98my_vn {
  d: path("M23.787 20.789a1.988 1.988 0 0 0-3.976 0v1.685c0 .193.157.35.35.35h3.276a.35.35 0 0 0 .35-.35z");
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v_irgab5s {
  stop-color: var(--svg-color--edc2aa, #EDC2AA);
}

.v4xj77b7s {
  stop-color: var(--svg-color--ffd9c4, #FFD9C4);
}

.ve7x40mpw {
  stop-color: var(--svg-color--f1c3a4, #F1C3A4);
}

.vjrh0pbek {
  cx: 18.495px;
  cy: 12.767px;
  r: 0.481px;
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.vuyf4ac8d {
  fill: var(--svg-color--000, #000);
  d: path("M15.379 12.908a.246.246 0 0 0-.247-.247a.246.246 0 0 0-.22.36h.437a.24.24 0 0 0 .03-.113");
}

.w23km64va {
  d: path("M24.755 5.431a.399.399 0 1 0-.796-.033v.46a.38.38 0 0 0 .757.032z");
}

.w8ndeybvy {
  d: path("m22.94 28.17l.472-5.464h-3.218l.477 5.465z");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl3r7lcsl {
  stop-color: var(--svg-color--ffd6c1, #FFD6C1);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xjez76bam {
  stop-color: var(--svg-color--1071cb, #1071CB);
}

.xmhbxgbvu {
  stop-color: var(--svg-color--ffd9c0, #FFD9C0);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yi8xsxb7e {
  stop-color: var(--svg-color--3770bc, #3770BC);
  stop-opacity: 0;
}

.yqz616b0p {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m16.005 12.773l-.258.822a.26.26 0 0 0 .252.339h.38a.262.262 0 0 0 .252-.339l-.257-.822c-.055-.182-.312-.182-.37 0");
}

.yufx44vic {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.19 14.46a1.45 1.45 0 0 1-.67-.158c-.067-.034-.138.04-.096.1c.162.246.444.41.766.41a.92.92 0 0 0 .765-.41c.042-.062-.029-.134-.095-.1a1.45 1.45 0 0 1-.67.159");
}

.yv16imbst {
  stop-color: var(--svg-color--d9aa99, #D9AA99);
}

.yv6n4cc_b {
  d: path("M8.001 6.573h2.46v7.269h-2.46z");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z_2l9eb3h {
  d: path("m9.675 28.6l-.513-5.894h3.22l-.534 5.966z");
}

.z0dt5e0_f {
  stop-color: var(--svg-color--edb7a7, #EDB7A7);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zp8bw1b5w {
  d: path("M8.787 20.789a1.988 1.988 0 1 1 3.977 0v1.685a.35.35 0 0 1-.35.35H9.137a.35.35 0 0 1-.35-.35z");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
