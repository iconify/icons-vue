<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXdKPWb)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iKan2qb)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iC4wQzc)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iJ3DPki)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#i5lzeDc)"><path class="g11vnob-s"/></g><g filter="url(#iu0px8c)"><path class="ytl8wkbiv"/></g><g filter="url(#igbslXb)"><path class="s99p66ikg"/></g><g filter="url(#ictXL1c)"><path class="pv3dgeoha"/></g><g filter="url(#i0zpSLb)"><path fill="url(#iLoyFXc)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#ipndBuc)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#ilTeCRt)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#i4HlMie)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iipbqMb)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iOwMfSd)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iBmCcdc)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iEUlYne)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iGSpBVd)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iAyu3ac)" clip-rule="evenodd" class="qdirzvb9l"/><path fill="url(#iL5rRHe)" clip-rule="evenodd" class="qdirzvb9l"/></g><g filter="url(#ikTvB5r)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#iO4z7tS)"><path fill="url(#ioitlCc)" class="dv6-6mbxj"/></g><path fill="url(#ipQ5Pnc)" class="dv6-6mbxj"/><path fill="url(#i8KfH3d)" class="dv6-6mbxj"/><path fill="url(#iEdEbnd)" class="dv6-6mbxj"/><path class="dxabh57cr"/><path fill="url(#i7QnpSd)" class="mh57-sx2c"/><path fill="url(#iJU4nte)" class="mh57-sx2c"/><g filter="url(#iXOXI4c)"><path fill="url(#iVQsxVd)" class="j-tweow-u"/><path fill="url(#i1oqYKe)" class="j-tweow-u"/><path fill="url(#i47ILGc)" class="j-tweow-u"/><path fill="url(#ia9WQcc)" class="j-tweow-u"/></g><path fill="url(#iuP6NMd)" class="eayua2tob"/><path fill="url(#iDv7Hjb)" class="eayua2tob"/><g filter="url(#ieBNTxz)"><path class="qnuw62bqm"/><path fill="url(#i40CHhd)" class="l99mnwbez"/><path fill="url(#iOc4Lne)" class="l99mnwbez"/></g><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#itC8Jgb)" class="z30kudb-o"/><g filter="url(#iK7VWmB)"><path class="nkr0e_-9b"/><path fill="url(#iciFMOe)" class="k-27-x9ja"/><path fill="url(#iwzkgkd)" class="k-27-x9ja"/></g><g filter="url(#i4m0oKb)"><path class="m3bis1bwo"/></g><path fill="url(#izDs5hc)" class="xgq6w0b8s"/><g filter="url(#i4GSLed)"><path class="cw_gb7c9k"/><path fill="url(#iSGVMGe)" class="my24k1swc"/></g><path fill="url(#inrcRqb)" class="my24k1swc"/><path fill="url(#iEr62fd)" class="my24k1swc"/><path fill="url(#iWroyTd)" class="js5y7fb5r"/><path fill="url(#izNTKdc)" class="js5y7fb5r"/><path fill="url(#isWFNye)" class="js5y7fb5r"/><path fill="url(#iKByDMe)" class="js5y7fb5r"/><path fill="url(#iBJnkMe)" class="js5y7fb5r"/><path fill="url(#iPzK2eN)" class="b6pcaeboe"/><path fill="url(#i6jZa1b)" class="b6pcaeboe"/><g filter="url(#i0mayyc)"><path class="zepkmwb6a"/><path fill="url(#iaToRcc)" class="uw9pt0beg"/><path fill="url(#i4dfdjc)" class="uw9pt0beg"/><path fill="url(#ihLxlKX)" class="uw9pt0beg"/></g><g filter="url(#iLq1ceb)"><path fill="url(#i1rpXhe)" class="u73f8386r"/></g><g filter="url(#iN79lNA)"><path fill="url(#iprmjKe)" class="arpmzcbgd"/></g><g filter="url(#ifivn7b)"><path class="ulxnrvr7k"/><path fill="url(#ic81doe)" class="hsbrvbc9q"/></g><g filter="url(#iQXqAIc)"><path class="nkz5zrf5z"/><path fill="url(#iTo8M7L)" class="b4tru1fmb"/></g><g filter="url(#iVBOGst)"><path fill="url(#iVE4gje)" class="h4d1g-bur"/><path fill="url(#iJdjkrc)" class="h4d1g-bur"/><path fill="url(#igTJJmd)" class="h4d1g-bur"/><path fill="url(#iR0SLye)" class="h4d1g-bur"/><path fill="url(#iLqrd5d)" class="h4d1g-bur"/><path fill="url(#ifxUGqd)" class="h4d1g-bur"/><path fill="url(#iIsRT0d)" class="h4d1g-bur"/></g><path fill="url(#iUIjf0b)" class="h4d1g-bur"/><g filter="url(#izS8R5b)"><path class="qlrvzy7qu"/></g><g filter="url(#i4ukkIc)"><path fill="url(#iAkF49c)" class="av7l0hezh"/><path fill="url(#iunxq2c)" class="av7l0hezh"/><path fill="url(#iEf3iJI)" class="av7l0hezh"/><path fill="url(#iVvDCac)" class="av7l0hezh"/></g><g filter="url(#it7Mvgb)"><path stroke="url(#iK9MMAb)" class="q55ko9bhn"/></g><path class="hglrvtbfo"/><g filter="url(#iXoGBxg)"><path class="cnhtbdbci"/></g><g filter="url(#iJdAhjd)"><path class="ac2azebwf"/></g><g filter="url(#iSolP3d)"><path class="kbfb5tcog"/></g><g filter="url(#iTMQpLc)"><path clip-rule="evenodd" class="lxh7nsbbr"/></g><path class="gdquz6cej"/><path fill="url(#iUNN8Tb)" class="iw46nndlz"/><path class="svv9xn9nq"/><g filter="url(#iFgqDMb)"><path class="xa_kmvbmy"/><path fill="url(#iiZC8Vd)" class="tb8wxt3nt"/></g><g filter="url(#iqpY0eF)"><path fill="url(#iiaXxBd)" class="cr9jcuwgp"/></g><path class="mjqgh-atk"/><path fill="url(#idN6gKc)" class="e8af0oton"/><path class="mu_wedbtg"/><g filter="url(#iQxLnGe)"><path fill="url(#iKBy8qv)" class="xwm7hj7qw"/></g><g filter="url(#ieT25ed)"><ellipse transform="rotate(-27.914 14.954 7.608)" class="c31rvbyry"/><ellipse fill="url(#ifcCdvd)" transform="rotate(-27.914 14.954 7.608)" class="bx2vmc6sl"/></g><g filter="url(#izAv4My)"><path fill="url(#ihXs7Sh)" class="gwc15kbor"/><path fill="url(#ijiFVvd)" class="gwc15kbor"/></g><g filter="url(#irgXOFb)"><path fill="url(#i9Tjetd)" class="v5ut1kbzr"/><path fill="url(#iJHJVJc)" class="v5ut1kbzr"/><path fill="url(#iN06Hmc)" class="v5ut1kbzr"/></g><g filter="url(#i0aMehd)"><path stroke="url(#iacKR8b)" class="ppfc51bqt"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ipndBuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.22975 .66218 -.93794 1.74188 17.702 9.356)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="ilTeCRt" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.95147 -1.1757 0 14.027 8.802)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="i4HlMie" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.43952 -2.5412 0 16.028 8.842)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iipbqMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.54332 .70508 -.6846 -.52754 13.878 8.052)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iOwMfSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20475 1.10078 -1.14625 -.21321 14.137 6.985)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iBmCcdc" cx="0" cy="0" r="1" gradientTransform="matrix(.47974 .9257 -1.76342 .91389 14.567 4.775)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iEUlYne" cx="0" cy="0" r="1" gradientTransform="matrix(-.48442 .52846 -.73852 -.67697 18.436 5.395)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iGSpBVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.80733 .23487 -.51105 -1.75665 19.316 7.538)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iAyu3ac" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 11.608 1.48)scale(2.04154 2.93189)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iL5rRHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0037 -.60183 .19732 -.00121 14.843 5.867)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="ipQ5Pnc" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.217 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="i47ILGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17187 2.9198 -.50904 -.02996 15.382 25.78)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="qw90o_byh"/><stop offset="1" class="ampfxn_6u"/></radialGradient><radialGradient id="ia9WQcc" cx="0" cy="0" r="1" gradientTransform="rotate(136.079 3.684 13.408)scale(1.17131 2.12121)" gradientUnits="userSpaceOnUse"><stop class="h969d3nbv"/><stop offset="1" class="p6kodn5gp"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iOc4Lne" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="lhl06-bha"/><stop offset="1" class="l473kpbea"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="itC8Jgb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.564 3.998 7.72)scale(.69215 .70844)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="qtbbj-y7w"/><stop offset="1" class="ocvnedcjc"/></radialGradient><radialGradient id="iciFMOe" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="y9drs-b-r"/><stop offset=".995" class="o-5xddb6x"/></radialGradient><radialGradient id="iwzkgkd" cx="0" cy="0" r="1" gradientTransform="rotate(119.914 -.645 10.001)scale(.98695 .40009)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="s2zpt4bdz"/><stop offset="1" class="iwjfcrbly"/></radialGradient><radialGradient id="iSGVMGe" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.875 -2.0833 .9722 21.944 8.247)" gradientUnits="userSpaceOnUse"><stop class="em3moybkz"/><stop offset="1" class="mtf4q5bqt"/></radialGradient><radialGradient id="inrcRqb" cx="0" cy="0" r="1" gradientTransform="matrix(.26644 -4.07813 1.3228 .08642 23.615 13.013)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="er1wy7bvb"/><stop offset="1" class="yv86un7fh"/></radialGradient><radialGradient id="iEr62fd" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 6.033 12.706)scale(.35113 2.04974)" gradientUnits="userSpaceOnUse"><stop class="km2h82bty"/><stop offset="1" class="en0ycmbdo"/></radialGradient><radialGradient id="isWFNye" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1.0625 -3.8587 .39722 15.607 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="nixijjbfx"/><stop offset="1" class="gakt19nxd"/></radialGradient><radialGradient id="iPzK2eN" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="muaav7b6p"/><stop offset="1" class="mudxz8mau"/></radialGradient><radialGradient id="i6jZa1b" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 1.15915 -2.52272 .37405 15.764 10.01)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="cqyclubjo"/><stop offset=".959" class="w5bqzmbgl"/></radialGradient><radialGradient id="iprmjKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.08995 -.49543 .6049 1.33078 17.797 8.104)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="ic81doe" cx="0" cy="0" r="1" gradientTransform="matrix(.5358 -.19817 .19817 .5358 18.04 8.015)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iTo8M7L" cx="0" cy="0" r="1" gradientTransform="matrix(-.47035 0 0 -.44992 13.985 7.911)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iVE4gje" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.798 5.734)scale(3.13611 4.19763)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iJdjkrc" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.44 6.083)scale(1.04512 .88671)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="igTJJmd" cx="0" cy="0" r="1" gradientTransform="matrix(.36649 -1.77135 2.24752 .465 15.074 10.646)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iR0SLye" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.25821 -5.17493 0 15.914 7.464)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iLqrd5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37452 .65664 -1.13053 -4.0882 16.303 8.401)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="ifxUGqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50392 .61845 0 17.036 7.493)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iIsRT0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59554 .68253 0 15.188 7.53)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iUIjf0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.58983 0 0 -1.94173 18.26 8.144)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iunxq2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.30541 -1.07273 .61383 -.17476 16.372 8.462)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iUNN8Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35485 -.56443 0 16.983 7.65)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iiZC8Vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10135 -.1306 .17982 -.13954 16.883 7.687)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idN6gKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35485 -.56443 0 15.072 7.65)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ifcCdvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00338 -.21592 .25954 -.00406 14.947 7.746)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihXs7Sh" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 6.274 5.928)scale(2.35129 1.02547)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="ijiFVvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3587 .97065 -.4797 -.67149 14.778 5.106)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="i9Tjetd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95696 1.99464 -2.83205 -1.35872 16.813 4.353)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iJHJVJc" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 6.713 8.915)scale(1.50638 3.1569)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iN06Hmc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49621 -2.83207 2.5317 -1.33753 16.532 7.368)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="iXdKPWb" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1142" result="effect2_innerShadow_4002_1142"/></filter><filter id="iKan2qb" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1142" result="effect2_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1142" result="effect3_innerShadow_4002_1142"/></filter><filter id="iC4wQzc" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1142" result="effect2_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1142" result="effect3_innerShadow_4002_1142"/></filter><filter id="iJ3DPki" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="i5lzeDc" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1142" result="effect2_dropShadow_4002_1142"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1142" result="shape"/></filter><filter id="iu0px8c" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1142" result="effect2_dropShadow_4002_1142"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1142" result="shape"/></filter><filter id="igbslXb" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1142" result="effect2_dropShadow_4002_1142"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1142" result="shape"/></filter><filter id="ictXL1c" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1142" result="effect2_dropShadow_4002_1142"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1142" result="shape"/></filter><filter id="i0zpSLb" width="6.826" height="6.826" x="12.74" y="3.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="ikTvB5r" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iO4z7tS" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iXOXI4c" width="2.97" height="9.929" x="13.318" y="19.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.658824 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="ieBNTxz" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.576471 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iK7VWmB" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.564706 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.423529 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1142" result="effect2_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.619608 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1142" result="effect3_innerShadow_4002_1142"/></filter><filter id="i4m0oKb" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="i4GSLed" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.556863 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="i0mayyc" width="6.349" height="5.065" x="13.14" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.415686 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1142" result="effect2_innerShadow_4002_1142"/></filter><filter id="iLq1ceb" width="1.509" height="1.409" x="13.272" y="7.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iN79lNA" width="1.409" height="1.659" x="17.438" y="6.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="ifivn7b" width="1.941" height="1.941" x="17.172" y="6.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".25"/></filter><filter id="iQXqAIc" width="1.441" height="1.441" x="13.265" y="7.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".125"/></filter><filter id="iVBOGst" width="4.463" height="4.813" x="13.797" y="5.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="izS8R5b" width="1.822" height="2.174" x="15.046" y="7.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".25"/></filter><filter id="i4ukkIc" width="1.022" height="1.374" x="15.517" y="7.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".05"/></filter><filter id="it7Mvgb" width="1.646" height=".693" x="15.205" y="8.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".025"/></filter><filter id="iXoGBxg" width="1.427" height=".563" x="16.328" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iJdAhjd" width="1.427" height=".563" x="14.302" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iSolP3d" width="1.186" height=".59" x="14.361" y="6.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iTMQpLc" width="1.186" height=".59" x="16.733" y="6.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1142"/></filter><filter id="iFgqDMb" width=".456" height=".417" x="16.606" y="7.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".05"/></filter><filter id="iqpY0eF" width=".615" height=".625" x="16.918" y="7.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".1"/></filter><filter id="iQxLnGe" width=".657" height=".68" x="14.972" y="7.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".1"/></filter><filter id="ieT25ed" width=".512" height=".42" x="14.698" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".05"/></filter><filter id="izAv4My" width="2.026" height="2.126" x="13.17" y="4.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".125"/></filter><filter id="irgXOFb" width="3.885" height="2.512" x="14.585" y="4.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".05"/></filter><filter id="i0aMehd" width=".838" height="1.348" x="14.462" y="4.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1142" stdDeviation=".125"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iLoyFXc" x1="18.083" x2="14.912" y1="4.867" y2="10.753" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iVQsxVd" x1="15.288" x2="12.882" y1="25.263" y2="25.294" gradientUnits="userSpaceOnUse"><stop offset=".113" class="dwuisxbps"/><stop offset="1" class="jot7ajumx"/></linearGradient><linearGradient id="i1oqYKe" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="xnu-7l9ks"/><stop offset="1" class="a4yl9qxqh"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="i40CHhd" x1="18.757" x2="18.351" y1="24.364" y2="24.091" gradientUnits="userSpaceOnUse"><stop offset=".202" class="o74y7ni4m"/><stop offset="1" class="c_2-erh-s"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="izDs5hc" x1="8.209" x2="7.425" y1="14.716" y2="15.269" gradientUnits="userSpaceOnUse"><stop offset=".337" class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><linearGradient id="iWroyTd" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="z9-ns_cqv"/><stop offset="1" class="voshhcbhx"/></linearGradient><linearGradient id="izNTKdc" x1="13.267" x2="15.139" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="w8z9c1bqk"/><stop offset="1" class="d1stbzbsu"/></linearGradient><linearGradient id="iKByDMe" x1="18.792" x2="16.607" y1="13.948" y2="13.948" gradientUnits="userSpaceOnUse"><stop class="eo1g38slj"/><stop offset="1" class="s89mq5-5f"/></linearGradient><linearGradient id="iBJnkMe" x1="18.96" x2="17.959" y1="14.225" y2="14.225" gradientUnits="userSpaceOnUse"><stop offset=".049" class="bpn-u35sy"/><stop offset="1" class="ukj380brt"/></linearGradient><linearGradient id="iaToRcc" x1="13.14" x2="15.351" y1="18.9" y2="18.9" gradientUnits="userSpaceOnUse"><stop class="c2g5jlmdp"/><stop offset="1" class="j9-ktqfbw"/></linearGradient><linearGradient id="i4dfdjc" x1="19.255" x2="16.729" y1="18.309" y2="18.9" gradientUnits="userSpaceOnUse"><stop offset=".349" class="hta3d8bay"/><stop offset="1" class="yezlp2beb"/></linearGradient><linearGradient id="ihLxlKX" x1="19.489" x2="18.607" y1="18.386" y2="18.614" gradientUnits="userSpaceOnUse"><stop class="wg5i7s-vd"/><stop offset="1" class="pql-90wca"/></linearGradient><linearGradient id="i1rpXhe" x1="13.272" x2="14.568" y1="7.949" y2="7.949" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iAkF49c" x1="16.028" x2="16.028" y1="8.804" y2="7.629" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iEf3iJI" x1="15.57" x2="15.944" y1="8.47" y2="8.516" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iVvDCac" x1="16.028" x2="16.028" y1="8.844" y2="8.577" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iK9MMAb" x1="15.709" x2="15.907" y1="9.491" y2="9.109" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iiaXxBd" x1="17.324" x2="17.187" y1="7.673" y2="7.758" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKBy8qv" x1="15.398" x2="15.261" y1="7.673" y2="7.758" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iacKR8b" x1="14.762" x2="15.001" y1="5.197" y2="5.754" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-fairy" /></template>
<style>
.a4yl9qxqh {
  stop-color: var(--svg-color--fcb63b, #FCB63B);
  stop-opacity: 0;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ac2azebwf {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.528 7.662c-.116-.204-.293-.366-.673-.366a.73.73 0 0 0-.47.162c-.117.095-.102.216-.01.262l.243.139c.285-.092.601-.105.91-.197");
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.ampfxn_6u {
  stop-color: var(--svg-color--e9af19, #E9AF19);
  stop-opacity: 0;
}

.arpmzcbgd {
  d: path("M18.142 8.616a.705.705 0 1 0 0-1.41a.705.705 0 0 0 0 1.41");
}

.av7l0hezh {
  d: path("m15.86 7.753l-.232.745a.236.236 0 0 0 .228.306h.344a.237.237 0 0 0 .228-.306l-.232-.745c-.05-.165-.283-.165-.335 0");
}

.b4tru1fmb {
  d: path("M13.985 8.382a.47.47 0 1 0 0-.94a.47.47 0 0 0 0 .94");
}

.b6pcaeboe {
  d: path("M15.07 10.136v.699a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.699z");
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bpn-u35sy {
  stop-color: var(--svg-color--9771bf, #9771BF);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bx2vmc6sl {
  cx: 14.954px;
  cy: 7.608px;
  rx: 0.17px;
  ry: 0.086px;
}

.c_2-erh-s {
  stop-color: var(--svg-color--ffc93f, #FFC93F);
  stop-opacity: 0;
}

.c2g5jlmdp {
  stop-color: var(--svg-color--67568f, #67568F);
}

.c31rvbyry {
  cx: 14.954px;
  cy: 7.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.17px;
  ry: 0.086px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnhtbdbci {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.528 7.662c.117-.204.293-.366.674-.366c.166 0 .327.046.47.162c.117.095.101.216.01.262l-.243.139c-.286-.092-.601-.105-.91-.197");
}

.cqyclubjo {
  stop-color: var(--svg-color--e08d23, #E08D23);
}

.cr9jcuwgp {
  d: path("M17.333 7.78a.37.37 0 0 0-.102-.202l-.113.124l.051.1z");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cw_gb7c9k {
  fill: var(--svg-color--ffda42, #FFDA42);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.d1stbzbsu {
  stop-color: var(--svg-color--8664c8, #8664C8);
  stop-opacity: 0;
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

.dv6-6mbxj {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .129.376l-.735.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.319.237l-.864-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.dwuisxbps {
  stop-color: var(--svg-color--ffd240, #FFD240);
}

.dxabh57cr {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.39v-.861h5.525v.82a49 49 0 0 1-5.525.041");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e8af0oton {
  d: path("M15.072 7.44a.39.39 0 0 0-.377.494h.754a.393.393 0 0 0-.378-.493");
}

.eayua2tob {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.em3moybkz {
  stop-color: var(--svg-color--f2b336, #F2B336);
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.en0ycmbdo {
  stop-color: var(--svg-color--f2b133, #F2B133);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eo1g38slj {
  stop-color: var(--svg-color--ac8de6, #AC8DE6);
}

.er1wy7bvb {
  stop-color: var(--svg-color--ffdb3e, #FFDB3E);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.gakt19nxd {
  stop-color: var(--svg-color--8e6ccf, #8E6CCF);
  stop-opacity: 0;
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gdquz6cej {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.075 7.322c.286 0 .528.197.594.464a.12.12 0 0 1-.118.149h-.977a.1.1 0 0 1-.1-.12a.61.61 0 0 1 .601-.493");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gwc15kbor {
  d: path("M13.885 5.278c.272-.242.665-.245.885-.206l.176.565a.34.34 0 0 0-.297.103c-.2.552-.886.856-1.204.94c-.066-.654-.03-.984.44-1.402");
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h4d1g-bur {
  d: path("M13.8 7.358h.006l-.004-.116l-.005-.134c.01-.415.252-.576.355-.63l.022-.009l.023-.009a1 1 0 0 0 .52-.54l.037-.085a.115.115 0 0 1 .202-.023c.314.46.84.733 1.396.733h1.41c.08 0 .474.038.498.584l-.052 1.345c-.054 1.227-1.013 2.051-2.182 2.051s-2.129-.824-2.183-2.05z");
}

.h969d3nbv {
  stop-color: var(--svg-color--d28436, #D28436);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hglrvtbfo {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.028 9.186c-.228 0-.442-.055-.622-.15c-.062-.033-.128.038-.089.095a.846.846 0 0 0 1.423 0c.039-.06-.027-.128-.09-.096c-.18.096-.391.151-.622.151");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hsbrvbc9q {
  d: path("M18.142 8.382a.47.47 0 1 0 0-.941a.47.47 0 0 0 0 .94");
}

.hta3d8bay {
  stop-color: var(--svg-color--9882d5, #9882D5);
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iw46nndlz {
  d: path("M16.984 7.44a.39.39 0 0 1 .376.494h-.754a.392.392 0 0 1 .378-.493");
}

.iwjfcrbly {
  stop-color: var(--svg-color--d08154, #D08154);
  stop-opacity: 0;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j-tweow-u {
  d: path("M13.318 29.589v-9.484l2.32.062l-.495 8.676a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.j9-ktqfbw {
  stop-color: var(--svg-color--8266c3, #8266C3);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jot7ajumx {
  stop-color: var(--svg-color--f6ae2e, #F6AE2E);
}

.js5y7fb5r {
  d: path("M16.017 10.71a24 24 0 0 0-1.985.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a24 24 0 0 0-1.985-.163h-.026");
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.kbfb5tcog {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("M14.54 7.133a.118.118 0 0 1-.121-.2v-.001h.002l.004-.003l.014-.008l.05-.026c.044-.02.105-.047.18-.07c.15-.048.357-.088.582-.048a.118.118 0 0 1-.04.23a1 1 0 0 0-.47.041a1 1 0 0 0-.19.08z");
}

.km2h82bty {
  stop-color: var(--svg-color--f2b133, #F2B133);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
}

.l473kpbea {
  stop-color: var(--svg-color--ffe447, #FFE447);
  stop-opacity: 0;
}

.l99mnwbez {
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.062.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhl06-bha {
  stop-color: var(--svg-color--ffe447, #FFE447);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lxh7nsbbr {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m17.662 6.932l-.06.101za.118.118 0 0 1-.12.2h-.002l-.05-.026a1 1 0 0 0-.15-.059a1 1 0 0 0-.47-.04a.117.117 0 1 1-.04-.231c.225-.04.433 0 .582.047a1.4 1.4 0 0 1 .244.105l.004.002z");
}

.m3bis1bwo {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mh57-sx2c {
  d: path("M13.267 16.39v-.861h5.525v.82a49 49 0 0 1-5.525.041");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mjqgh-atk {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.981 7.322a.61.61 0 0 0-.593.464a.12.12 0 0 0 .117.149h.977a.1.1 0 0 0 .1-.12a.614.614 0 0 0-.6-.493");
}

.mtf4q5bqt {
  stop-color: var(--svg-color--f2b336, #F2B336);
  stop-opacity: 0;
}

.mu_wedbtg {
  fill: var(--svg-color--000, #000);
  d: path("M15.295 7.831c0-.124-.1-.223-.223-.223a.223.223 0 0 0-.2.326h.396a.2.2 0 0 0 .027-.103");
}

.muaav7b6p {
  stop-color: var(--svg-color--f79d25, #F79D25);
}

.mudxz8mau {
  stop-color: var(--svg-color--ffbe35, #FFBE35);
}

.my24k1swc {
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nixijjbfx {
  stop-color: var(--svg-color--7b3459, #7B3459);
}

.nkr0e_-9b {
  fill: var(--svg-color--ffc337, #FFC337);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.nkz5zrf5z {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M13.985 8.382a.47.47 0 1 0 0-.94a.47.47 0 0 0 0 .94");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o74y7ni4m {
  stop-color: var(--svg-color--f4c04c, #F4C04C);
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.ocvnedcjc {
  stop-color: var(--svg-color--d59d43, #D59D43);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p6kodn5gp {
  stop-color: var(--svg-color--f1ab1f, #F1AB1F);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppfc51bqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.762 5.047c.01.106.103.505.239.747");
}

.pql-90wca {
  stop-color: var(--svg-color--9f8cca, #9F8CCA);
  stop-opacity: 0;
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.q55ko9bhn {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.028 9.186c-.228 0-.442-.055-.622-.15c-.062-.033-.128.038-.089.095a.846.846 0 0 0 1.423 0c.039-.06-.027-.128-.09-.096c-.18.096-.391.151-.622.151Z");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qdirzvb9l {
  fill-rule: evenodd;
  d: path("M19.175 8.529a1.44 1.44 0 0 0 .024-1.197h.002a1.4 1.4 0 0 0-.123-.225v-.001c-.152-.23-.231-.5-.231-.776v-.004c0-.798-.647-1.445-1.445-1.445a.24.24 0 0 1-.2-.102a1.447 1.447 0 0 0-2.348 0a.25.25 0 0 1-.2.102h-.037c-.78.02-1.407.66-1.407 1.445v.004c0 .275-.08.546-.23.776l-.002.002a1.45 1.45 0 0 0-.096 1.42a.23.23 0 0 1 0 .2a1.407 1.407 0 0 0 1.267 2.025h3.758a1.407 1.407 0 0 0 1.268-2.025a.23.23 0 0 1 0-.2m-5.37-1.17H13.8l.525 1.03c.054 1.228.533 0 1.703 0s1.68 1.367 1.734.14l.497-1.4c-.023-.546-.418-.584-.497-.584h-1.41a1.69 1.69 0 0 1-1.396-.733a.115.115 0 0 0-.203.023l-.036.085a1 1 0 0 1-.52.54l-.023.01l-.022.008c-.104.054-.346.215-.355.63l.004.134z");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qlrvzy7qu {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.856 7.814l-.299.744a.236.236 0 0 0 .228.306h.344a.237.237 0 0 0 .228-.306l-.232-.744c-.05-.165-.216-.165-.269 0");
}

.qnuw62bqm {
  fill: var(--svg-color--ffc93e, #FFC93E);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.062.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.qtbbj-y7w {
  stop-color: var(--svg-color--cb8139, #CB8139);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw90o_byh {
  stop-color: var(--svg-color--bc8531, #BC8531);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s2zpt4bdz {
  stop-color: var(--svg-color--d08154, #D08154);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s89mq5-5f {
  stop-color: var(--svg-color--9673d5, #9673D5);
  stop-opacity: 0;
}

.s99p66ikg {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.667l.84.086a.21.21 0 1 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.svv9xn9nq {
  fill: var(--svg-color--000, #000);
  d: path("M16.761 7.831c0-.124.1-.223.224-.223a.223.223 0 0 1 .198.326h-.395a.2.2 0 0 1-.027-.103");
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.tb8wxt3nt {
  d: path("M16.955 7.524c.028.037-.03.082-.096.132c-.066.049-.115.084-.143.047s.003-.108.07-.157c.065-.05.141-.06.17-.022");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u73f8386r {
  d: path("M13.976 8.616a.705.705 0 1 0 0-1.41a.705.705 0 0 0 0 1.41");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uin7i86hm {
  stop-color: var(--svg-color--ffc337, #FFC337);
}

.ukj380brt {
  stop-color: var(--svg-color--a585e1, #A585E1);
  stop-opacity: 0;
}

.ulxnrvr7k {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M18.142 8.382a.47.47 0 1 0 0-.941a.47.47 0 0 0 0 .94");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uw9pt0beg {
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v5ut1kbzr {
  d: path("M15.764 4.5c-.496-.11-1.028.418-1.079.602c.675 1.585 1.712 1.434 2.863 1.306c.688-.076.763.237.822.39c-.191-1.777-1.476-2.049-2.606-2.298");
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

.vj70_lxns {
  stop-color: var(--svg-color--ffc337, #FFC337);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.voshhcbhx {
  stop-color: var(--svg-color--8466c6, #8466C6);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vsr9738qr {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w5bqzmbgl {
  stop-color: var(--svg-color--e08d23, #E08D23);
  stop-opacity: 0;
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.w8z9c1bqk {
  stop-color: var(--svg-color--6f5187, #6F5187);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wg5i7s-vd {
  stop-color: var(--svg-color--8569c7, #8569C7);
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xa_kmvbmy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.955 7.524c.028.037-.03.082-.096.132c-.066.049-.115.084-.143.047s.003-.108.07-.157c.065-.05.141-.06.17-.022");
}

.xgq6w0b8s {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.xnu-7l9ks {
  stop-color: var(--svg-color--fcb63b, #FCB63B);
}

.xwm7hj7qw {
  d: path("M15.429 7.786c0-.127-.103-.21-.13-.236l-.127.122l.078.158z");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y9drs-b-r {
  stop-color: var(--svg-color--e79b27, #E79B27);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yezlp2beb {
  stop-color: var(--svg-color--8467c6, #8467C6);
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

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yv86un7fh {
  stop-color: var(--svg-color--ffdb3e, #FFDB3E);
  stop-opacity: 0;
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z9-ns_cqv {
  stop-color: var(--svg-color--916ed5, #916ED5);
}

.zepkmwb6a {
  fill: var(--svg-color--8569c7, #8569C7);
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

</style>
