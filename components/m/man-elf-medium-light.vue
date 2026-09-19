<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCDvIfd)"><path class="pqpxg6gcd"/><path fill="url(#iUhI09c)" class="z-thopeux"/><path fill="url(#ihWU4vd)" class="z-thopeux"/></g><g filter="url(#ij71LZc)"><path class="j9cj5qbuy"/><path fill="url(#iz6GOIb)" class="z-thopeux"/><path fill="url(#iOivUbb)" class="z-thopeux"/></g><g filter="url(#iaRqOBb)"><path class="mcb3mdbmq"/><path fill="url(#ibuxX9V)" class="z-thopeux"/></g><g filter="url(#iqxXUhb)"><path class="nihdl4b3y"/><path fill="url(#imc1MXd)" class="z-thopeux"/><path fill="url(#iROJcPd)" class="z-thopeux"/></g><path fill="url(#igOI3Jc)" class="z-thopeux"/><path fill="url(#ijIM4he)" class="z-thopeux"/><g filter="url(#iccEOce)"><path class="oq0kvn9yx"/><path fill="url(#iQNKhUd)" class="b4mo-29ij"/><path fill="url(#i9Vqwjj)" class="b4mo-29ij"/></g><path class="ik39jqbsn"/><path fill="url(#iTsW5Nc)" class="z77zzmbkv"/><path fill="url(#iQcA7En)" class="z77zzmbkv"/><path fill="url(#iOfjqcd)" class="z77zzmbkv"/><path fill="url(#isgVVHd)" class="z77zzmbkv"/><path fill="url(#ibiEGBb)" class="z77zzmbkv"/><path class="uf8v-8bxn"/><path fill="url(#iP6UBmc)" class="wifu-cbwd"/><path fill="url(#ihNLNpd)" class="wifu-cbwd"/><path fill="url(#iER4OWb)" class="wifu-cbwd"/><path class="h68lkf1_a"/><path fill="url(#izBzNGe)" class="ps0fa7bxo"/><path fill="url(#ie411je)" class="ps0fa7bxo"/><path fill="url(#i8cymIQ)" class="ps0fa7bxo"/><path fill="url(#i8aYqre)" class="gr7x_rwbv"/><path fill="url(#iUn8IAz)" class="gr7x_rwbv"/><path fill="url(#iTXMv8b)" class="gr7x_rwbv"/><path fill="url(#ixwetQd)" class="gr7x_rwbv"/><path fill="url(#iLSaoWb)" class="gr7x_rwbv"/><path fill="url(#i5Lj3Yc)" class="gr7x_rwbv"/><path fill="url(#i82dLZi)" class="gr7x_rwbv"/><g filter="url(#i8KPCuc)"><path fill="url(#i2yDo0c)" class="a7a1m8boe"/></g><g filter="url(#iZFRc5W)"><path fill="url(#ivXyFxp)" class="jz8djgftu"/></g><g filter="url(#iKRrz0c)"><path fill="url(#iCWbHoe)" class="u3yytvbgg"/><path fill="url(#iuKX0Uc)" class="u3yytvbgg"/><path fill="url(#i6bZPzd)" class="u3yytvbgg"/><path fill="url(#icEs3vd)" class="u3yytvbgg"/><path fill="url(#iAGCnhe)" class="u3yytvbgg"/></g><path fill="url(#iXlG5uc)" class="xbdij97tt"/><path fill="url(#i5lCiQb)" class="xbdij97tt"/><path fill="url(#iOm6mQA)" class="xbdij97tt"/><path fill="url(#i7AxKKe)" class="xbdij97tt"/><path fill="url(#i5qF6Ee)" class="xbdij97tt"/><g filter="url(#iIvwmod)"><path class="tal-3wbcb"/></g><g filter="url(#idpcycb)"><path fill="url(#iYPAfAc)" class="gq_evtgpi"/><path fill="url(#ijhN5Ob)" class="gq_evtgpi"/></g><g filter="url(#igA8a0c)"><path fill="url(#iJmRUfx)" class="peclnma7n"/></g><g filter="url(#iVDocWc)"><path fill="url(#iXYI1bm)" class="zhwrqyb9y"/><path fill="url(#i3pLedb)" class="zhwrqyb9y"/></g><path fill="url(#ioj1Ozb)" class="da96dzbnj"/><path fill="url(#iNx7zJe)" class="da96dzbnj"/><g filter="url(#iKw02fd)"><path class="qqeozgbom"/></g><g filter="url(#iJHkmUd)"><path class="m_u5kn1ph"/></g><g filter="url(#iMBmhOe)"><path fill="url(#i880hAc)" class="c27hakbuc"/><path fill="url(#iTdK1db)" class="c27hakbuc"/><path fill="url(#ihKVWGg)" class="c27hakbuc"/><path fill="url(#iwO5oue)" class="c27hakbuc"/><path fill="url(#iq4rUZl)" class="c27hakbuc"/><path fill="url(#iFjMXle)" class="c27hakbuc"/></g><path fill="url(#iMhZHgc)" class="c27hakbuc"/><path fill="url(#iZA9s7c)" class="c27hakbuc"/><g filter="url(#ibOCUtd)"><path class="s_sn4ab8f"/></g><path class="pes_lybqy"/><path fill="url(#iX2ciYc)" class="y59bi164p"/><path fill="url(#iuHhvIb)" class="y59bi164p"/><path fill="url(#iuVEnXF)" class="y59bi164p"/><g filter="url(#ipQrLrb)"><path stroke="url(#i0En4Ob)" class="u9wqsy2sp"/></g><path class="t34bfozye"/><path class="a6tzm1b6f"/><path fill="url(#iP8FdEd)" class="qeihuuzsw"/><path class="qttrphznb"/><g filter="url(#icxTcWB)"><path class="c9cv27cck"/><path fill="url(#iszcHob)" class="ktl4e9bya"/></g><g filter="url(#i1vfiWX)"><path fill="url(#int20Xd)" class="cy93w4u1k"/></g><path class="oi6nokbyq"/><path fill="url(#ilstd7d)" class="y2vknabsu"/><path class="ikmt3oi5p"/><g filter="url(#i0792Xb)"><path fill="url(#iMuXX6c)" class="h_v8t2rlx"/></g><g filter="url(#iQicblb)"><ellipse transform="rotate(-27.914 13.547 9.956)" class="ebys0kbgr"/><ellipse fill="url(#igxaqOe)" transform="rotate(-27.914 13.547 9.956)" class="zy43xh0vl"/></g><g filter="url(#iqeSbNe)"><path stroke="url(#i9437oe)" class="apbgrhb_o"/></g><g filter="url(#iEu1kvc)"><path class="tkhb3b5oc"/></g><g filter="url(#i0ZrDJe)"><path class="gi4t7_tux"/></g><g filter="url(#iUrSNyb)"><path class="m5zytr9kz"/></g><g filter="url(#iXeOvne)"><path class="p0v6jucue"/></g><path fill="url(#igff5to)" class="cr9_z1bft"/><path fill="url(#in5wHue)" class="cr9_z1bft"/><path fill="url(#iCLmcsd)" class="cr9_z1bft"/><path fill="url(#itnot9c)" class="cr9_z1bft"/><path fill="url(#iUxKUte)" class="cr9_z1bft"/><path fill="url(#iaoe0Ee)" class="cr9_z1bft"/><path fill="url(#iXrGYyc)" class="cr9_z1bft"/><g filter="url(#idSyU9d)"><path fill="url(#iPNhVDc)" class="hii9ovp1o"/><path fill="url(#iOpvYDd)" class="hii9ovp1o"/></g><g filter="url(#iBMMcIb)"><path fill="url(#isZQ0mJ)" class="d1ruefb7x"/><path fill="url(#iTgeitb)" class="d1ruefb7x"/><path fill="url(#itoKL9d)" class="d1ruefb7x"/><path fill="url(#iwKl37z)" class="d1ruefb7x"/></g><path fill="url(#ilaJEee)" class="qylf6wbub"/><path fill="url(#iHRCiSc)" class="qylf6wbub"/><path fill="url(#iqWdVTd)" class="qylf6wbub"/><path fill="url(#imnlytb)" class="qylf6wbub"/><path fill="url(#i4PCG6d)" class="qylf6wbub"/><path fill="url(#iQPybpd)" class="qylf6wbub"/><path fill="url(#iRJILpP)" class="e_avwpn4q"/><defs><radialGradient id="iUhI09c" cx="0" cy="0" r="1" gradientTransform="rotate(119.999 8.37 12.873)scale(3.50014 9.06684)" gradientUnits="userSpaceOnUse"><stop class="jtnx86cjw"/><stop offset="1" class="ekl-imb0v"/></radialGradient><radialGradient id="ihWU4vd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="yap4pcbws"/><stop offset="1" class="b0havcbgv"/></radialGradient><radialGradient id="iz6GOIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="cva0eccxo"/><stop offset="1" class="yvvekm_dy"/></radialGradient><radialGradient id="iOivUbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="lp4if9b4k"/><stop offset="1" class="ofalufbug"/><stop offset="1" class="xilj489kn"/></radialGradient><radialGradient id="ibuxX9V" cx="0" cy="0" r="1" gradientTransform="rotate(134.256 9.246 11.762)scale(1.70162 4.86497)" gradientUnits="userSpaceOnUse"><stop class="jia0zn94s"/><stop offset="1" class="gabhccily"/></radialGradient><radialGradient id="imc1MXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="g34co-bjj"/><stop offset="1" class="j0iym8bez"/></radialGradient><radialGradient id="iROJcPd" cx="0" cy="0" r="1" gradientTransform="rotate(10.063 -70.522 122.48)scale(1.6639 4.72832)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="r-p883bfh"/><stop offset="1" class="jnmw52bvm"/></radialGradient><radialGradient id="igOI3Jc" cx="0" cy="0" r="1" gradientTransform="matrix(.73438 3.71875 -3.59965 .71086 22.41 14.285)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="ly3r7ebiq"/><stop offset="1" class="ja41yub3g"/></radialGradient><radialGradient id="ijIM4he" cx="0" cy="0" r="1" gradientTransform="rotate(-65.289 25.34 -8.468)scale(1.9436 3.02274)" gradientUnits="userSpaceOnUse"><stop class="m2zebkb3b"/><stop offset="1" class="lj7znd7rs"/></radialGradient><radialGradient id="iQNKhUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76854 -2.3752 2.9525 -.95534 9.87 17.754)" gradientUnits="userSpaceOnUse"><stop class="sl7vf6bvq"/><stop offset="1" class="k7vxnrb9w"/></radialGradient><radialGradient id="i9Vqwjj" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39063 .57888 -1.52227 -6.28657 12.111 14.59)" gradientUnits="userSpaceOnUse"><stop class="smbbml-bd"/><stop offset="1" class="vgv3oz8qv"/></radialGradient><radialGradient id="iQcA7En" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -11.6596 23.142 20.841)" gradientUnits="userSpaceOnUse"><stop class="nadkffb-q"/><stop offset="1" class="g8_ztm4ee"/></radialGradient><radialGradient id="iOfjqcd" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.531 5.262)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="n7-3g8b6a"/><stop offset="1" class="vn8pvc5iu"/></radialGradient><radialGradient id="isgVVHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51484 .49425 -5.62821 -5.8627 15.745 29.022)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="pa8e75o9n"/><stop offset="1" class="yngnm5bdn"/></radialGradient><radialGradient id="iP6UBmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 30.094)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="xfqn-nbow"/><stop offset="1" class="mv5v-89yi"/></radialGradient><radialGradient id="ihNLNpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.216)" gradientUnits="userSpaceOnUse"><stop class="tk0xf0bde"/><stop offset="1" class="d64kkcbzy"/></radialGradient><radialGradient id="izBzNGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.71323 -.26753 25.58 28.529)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="ybfplbczy"/><stop offset="1" class="y7tt4qbej"/></radialGradient><radialGradient id="i8cymIQ" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.623)" gradientUnits="userSpaceOnUse"><stop class="f6wdi7zjk"/><stop offset="1" class="mdqyvu4ex"/></radialGradient><radialGradient id="iTXMv8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.43994 -1.46875 8.18973 8.02909 15.736 29.935)" gradientUnits="userSpaceOnUse"><stop class="c11fd2rff"/><stop offset="1" class="qfs6aobhn"/></radialGradient><radialGradient id="ixwetQd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.282 11.452)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="iLSaoWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.31)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="w4q7dg2ti"/><stop offset="1" class="ro5kwtkrd"/></radialGradient><radialGradient id="i2yDo0c" cx="0" cy="0" r="1" gradientTransform="rotate(97.64 -1.695 18.198)scale(3.08805 1.1998)" gradientUnits="userSpaceOnUse"><stop class="xnfwhubut"/><stop offset="1" class="nd_uzdbib"/></radialGradient><radialGradient id="ivXyFxp" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.685)" gradientUnits="userSpaceOnUse"><stop class="kna63ccqu"/><stop offset="1" class="yg8va_99z"/></radialGradient><radialGradient id="iCWbHoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.22354 13.8281 0 16 21.287)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="g9gcawu6z"/><stop offset="1" class="hpb-k7b_o"/></radialGradient><radialGradient id="iuKX0Uc" cx="0" cy="0" r="1" gradientTransform="rotate(153.453 7.604 9.74)scale(9.41646 14.488)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="ngc6h6bst"/><stop offset="1" class="o5llqtbdv"/></radialGradient><radialGradient id="i6bZPzd" cx="0" cy="0" r="1" gradientTransform="matrix(6.05257 5.9867 -7.0398 7.11726 14.455 14.53)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="s1jm76o_g"/><stop offset="1" class="a0ve6ibhs"/></radialGradient><radialGradient id="icEs3vd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.94665 -1.47583 .92553 -2.47504 13.644 16.072)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="u9m-38uic"/><stop offset="1" class="dgp6vzbgz"/></radialGradient><radialGradient id="iAGCnhe" cx="0" cy="0" r="1" gradientTransform="rotate(120.992 5.816 12.626)scale(7.05716 2.39887)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="pf0n6ab7v"/><stop offset="1" class="xu2rljbva"/></radialGradient><radialGradient id="iXlG5uc" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -4.22173 2.03479 1.08445 16.142 20.563)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="q52fr3noq"/><stop offset="1" class="w_rnmcxom"/></radialGradient><radialGradient id="iOm6mQA" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4375 -7.82593 0 15.98 16.654)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="jcf69bbbv"/><stop offset="1" class="gv9gfeant"/></radialGradient><radialGradient id="i7AxKKe" cx="0" cy="0" r="1" gradientTransform="rotate(42.523 -14.575 24.68)scale(3.58325 2.63576)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="nt3ohmb5v"/><stop offset="1" class="hd78y1x_x"/></radialGradient><radialGradient id="iYPAfAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4697 -1.59165 3.40232 3.14166 8.65 11.062)" gradientUnits="userSpaceOnUse"><stop class="asqw3jbui"/><stop offset="1" class="q8p3q3bqx"/></radialGradient><radialGradient id="ijhN5Ob" cx="0" cy="0" r="1" gradientTransform="rotate(71.741 -1.116 10.387)scale(5.60855 3.99461)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="tvz40gbou"/><stop offset="1" class="si20u1b5q"/></radialGradient><radialGradient id="iXYI1bm" cx="0" cy="0" r="1" gradientTransform="matrix(2.96202 -3.23123 2.01258 1.8449 21.26 12.388)" gradientUnits="userSpaceOnUse"><stop class="sx3rjlbzk"/><stop offset="1" class="dkch0db-r"/></radialGradient><radialGradient id="i3pLedb" cx="0" cy="0" r="1" gradientTransform="rotate(-143.457 13.415 2.046)scale(1.81797 6.41679)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="dye_m7bch"/><stop offset="1" class="sd49k712l"/></radialGradient><radialGradient id="ioj1Ozb" cx="0" cy="0" r="1" gradientTransform="rotate(-143.844 7.348 4.223)scale(3.06704 1.99268)" gradientUnits="userSpaceOnUse"><stop class="t60ntu-wj"/><stop offset="1" class="nld201kgm"/></radialGradient><radialGradient id="iNx7zJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.14395 -1.05015 3.68181 4.01068 9.339 11.612)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="o20k0cbhd"/><stop offset="1" class="fp865pypd"/></radialGradient><radialGradient id="i880hAc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.89643 0 0 -9.1676 19.459 11.572)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ro__zqilq"/><stop offset=".659" class="g3-ejv53j"/></radialGradient><radialGradient id="iTdK1db" cx="0" cy="0" r="1" gradientTransform="matrix(-.6366 -1.32146 1.47878 -.71239 13.523 10.042)" gradientUnits="userSpaceOnUse"><stop class="c7ols3oue"/><stop offset="1" class="vs6qzmbeh"/></radialGradient><radialGradient id="ihKVWGg" cx="0" cy="0" r="1" gradientTransform="matrix(-.05774 -1.39619 1.68936 -.06986 18.371 10.243)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="fdx7kfdrk"/><stop offset="1" class="itpb-mb4j"/></radialGradient><radialGradient id="iwO5oue" cx="0" cy="0" r="1" gradientTransform="rotate(121.203 6.897 8.81)scale(2.45067 1.84691)" gradientUnits="userSpaceOnUse"><stop class="q439j4sbs"/><stop offset="1" class="ddoxxtboo"/></radialGradient><radialGradient id="iq4rUZl" cx="0" cy="0" r="1" gradientTransform="matrix(1.60556 3.3764 -7.05469 3.35469 14.352 6.128)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="vtamvdyqj"/><stop offset="1" class="uvyahya6g"/></radialGradient><radialGradient id="iMhZHgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94718 7 -10.78452 -1.45927 16.905 10.317)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="r324_0iwv"/><stop offset="1" class="f8if605-f"/></radialGradient><radialGradient id="i0En4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 -.625 1.875 .98437 14.614 14.31)" gradientUnits="userSpaceOnUse"><stop class="plcv9bbgt"/><stop offset="1" class="ehc1wgbxk"/></radialGradient><radialGradient id="iP8FdEd" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 6.732 9.582)scale(1.10543 1.21398)" gradientUnits="userSpaceOnUse"><stop class="gvj3_fmrq"/><stop offset="1" class="cap0zjbhu"/></radialGradient><radialGradient id="iszcHob" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.459 .671)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilstd7d" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.55 8.513)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="gvj3_fmrq"/><stop offset="1" class="cap0zjbhu"/></radialGradient><radialGradient id="igxaqOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.53 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igff5to" cx="0" cy="0" r="1" gradientTransform="rotate(117.277 8.224 7.024)scale(5.59037 9.77256)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset=".592" class="nvp34342a"/></radialGradient><radialGradient id="in5wHue" cx="0" cy="0" r="1" gradientTransform="matrix(.24995 2.72547 -2.26407 .20764 20.269 3.853)" gradientUnits="userSpaceOnUse"><stop class="r0z1khbsa"/><stop offset="1" class="luxz9w7iu"/></radialGradient><radialGradient id="iCLmcsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.81195 -.22697 .50807 6.29462 9.146 7.597)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="wyqd5ab8k"/><stop offset="1" class="l3hsrn8ob"/></radialGradient><radialGradient id="itnot9c" cx="0" cy="0" r="1" gradientTransform="rotate(109.616 4.569 5.918)scale(4.28106 1.6355)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="lgj7dyo1j"/><stop offset="1" class="wjq_rgywi"/></radialGradient><radialGradient id="iUxKUte" cx="0" cy="0" r="1" gradientTransform="matrix(.40617 -1.24218 6.61008 2.1614 10.474 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="k8f_-10rg"/><stop offset="1" class="l1kqit9sq"/></radialGradient><radialGradient id="iaoe0Ee" cx="0" cy="0" r="1" gradientTransform="rotate(-61.159 19.291 -12.774)scale(2.1374 3.76989)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="a4sfhobbt"/><stop offset="1" class="zeavlp0uo"/></radialGradient><radialGradient id="iXrGYyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.53117 -2.62839 5.63476 -1.13873 13.489 7.802)" gradientUnits="userSpaceOnUse"><stop class="cu84zd6ok"/><stop offset="1" class="k_huevcxk"/></radialGradient><radialGradient id="iOpvYDd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4597 1.15626 -.59734 -1.78734 16.12 3.935)" gradientUnits="userSpaceOnUse"><stop class="qfx4f-mat"/><stop offset="1" class="wy3jcw9jp"/></radialGradient><radialGradient id="isZQ0mJ" cx="0" cy="0" r="1" gradientTransform="matrix(3.46793 .19046 -.05313 .96742 19.002 4.707)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="vsbibr_ed"/><stop offset="1" class="zmahyob7y"/></radialGradient><radialGradient id="iTgeitb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3444 -2.26984 7.86767 4.6599 18.827 5.847)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="t0ficfbbx"/><stop offset="1" class="w1ahfsiui"/></radialGradient><radialGradient id="iwKl37z" cx="0" cy="0" r="1" gradientTransform="matrix(1.20814 -.69834 1.08437 1.87599 16.774 4.999)" gradientUnits="userSpaceOnUse"><stop class="qhrgfk8ap"/><stop offset="1" class="eiyn6rq_o"/></radialGradient><radialGradient id="imnlytb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.767 6.234)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="i4PCG6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 5.702)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iQPybpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.228 5.921)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="iRJILpP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.978 7.5)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><filter id="iCDvIfd" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.827451 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.807843 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1374" result="effect2_innerShadow_4002_1374"/></filter><filter id="ij71LZc" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.219608 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.215686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1374" result="effect2_innerShadow_4002_1374"/></filter><filter id="iaRqOBb" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.270588 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.282353 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1374" result="effect2_innerShadow_4002_1374"/></filter><filter id="iqxXUhb" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1374" result="effect2_innerShadow_4002_1374"/></filter><filter id="iccEOce" width="7.258" height="6.609" x="6.975" y="11.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.764706 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="i8KPCuc" width="2.581" height="5.008" x="14.415" y="20.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".25"/></filter><filter id="iZFRc5W" width="1.681" height="4.108" x="15.197" y="21.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="iKRrz0c" width="13.169" height="6.924" x="9.415" y="14.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="iIvwmod" width="4.058" height="5.011" x="20.39" y="8.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.596078 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="idpcycb" width="3.958" height="5.111" x="7.652" y="8.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.462745 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="igA8a0c" width="3.614" height="3.845" x="20.514" y="9.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".1"/></filter><filter id="iVDocWc" width="3.274" height="3.37" x="20.512" y="9.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".05"/></filter><filter id="iKw02fd" width="4.072" height="2.992" x="20.333" y="8.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".1"/></filter><filter id="iJHkmUd" width="3.202" height="2.498" x="8.089" y="9.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".05"/></filter><filter id="iMBmhOe" width="11.087" height="10.888" x="10.713" y="6.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.627451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="ibOCUtd" width="3.187" height="4.4" x="14.104" y="9.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".375"/></filter><filter id="ipQrLrb" width="3.668" height="1.523" x="14.166" y="13.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".075"/></filter><filter id="icxTcWB" width=".787" height=".696" x="17.448" y="9.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".05"/></filter><filter id="i1vfiWX" width=".891" height=".913" x="18.287" y="9.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".1"/></filter><filter id="i0792Xb" width=".986" height="1.04" x="13.845" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".1"/></filter><filter id="iQicblb" width=".913" height=".705" x="13.09" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".05"/></filter><filter id="iqeSbNe" width="2.916" height="3.003" x="13.723" y="18.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".125"/></filter><filter id="iEu1kvc" width="2.863" height="1.636" x="12.052" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="i0ZrDJe" width="2.563" height="1.336" x="12.078" y="7.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".15"/></filter><filter id="iUrSNyb" width="2.891" height="1.641" x="17.244" y="7.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1374"/></filter><filter id="iXeOvne" width="2.591" height="1.341" x="17.316" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".15"/></filter><filter id="idSyU9d" width="6.417" height="5.694" x="9.953" y="2.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".125"/></filter><filter id="iBMMcIb" width="6.176" height="5.689" x="15.87" y="2.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1374" stdDeviation=".125"/></filter><linearGradient id="iTsW5Nc" x1="15.049" x2="15.049" y1="30.094" y2="20.685" gradientUnits="userSpaceOnUse"><stop offset=".04" class="wogh8-v4o"/><stop offset="1" class="dt3zaebva"/></linearGradient><linearGradient id="ibiEGBb" x1="23.291" x2="22.822" y1="26.669" y2="26.669" gradientUnits="userSpaceOnUse"><stop offset=".327" class="iy0z3721s"/><stop offset="1" class="mm4k6y1ti"/></linearGradient><linearGradient id="iER4OWb" x1="8.912" x2="8.912" y1="30.094" y2="21.279" gradientUnits="userSpaceOnUse"><stop class="ycfa7kt7e"/><stop offset="1" class="kwgh1rbji"/></linearGradient><linearGradient id="ie411je" x1="24.142" x2="26.611" y1="29.466" y2="21.56" gradientUnits="userSpaceOnUse"><stop offset=".116" class="ht2yhibat"/><stop offset="1" class="p8cmnpbrm"/></linearGradient><linearGradient id="i8aYqre" x1="12.517" x2="22.705" y1="21.435" y2="31.091" gradientUnits="userSpaceOnUse"><stop class="te0saggyn"/><stop offset="1" class="wsy42fbgm"/></linearGradient><linearGradient id="iUn8IAz" x1="26.895" x2="21.238" y1="31.06" y2="26.873" gradientUnits="userSpaceOnUse"><stop class="gbkgrm1fg"/><stop offset="1" class="gb051imgb"/></linearGradient><linearGradient id="i5Lj3Yc" x1="15.015" x2="15.229" y1="28.829" y2="28.625" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="nstnghbkd"/></linearGradient><linearGradient id="i82dLZi" x1="19.002" x2="18.65" y1="22.138" y2="22.498" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="i5lCiQb" x1="15.098" x2="15.695" y1="19.848" y2="19.445" gradientUnits="userSpaceOnUse"><stop offset=".184" class="e8x8t6m4c"/><stop offset="1" class="sfwupzbpl"/></linearGradient><linearGradient id="i5qF6Ee" x1="17.642" x2="16.895" y1="18.748" y2="18.373" gradientUnits="userSpaceOnUse"><stop class="ytmccib4c"/><stop offset="1" class="zsyl6jyid"/></linearGradient><linearGradient id="iJmRUfx" x1="21.817" x2="23.407" y1="12.441" y2="9.413" gradientUnits="userSpaceOnUse"><stop offset=".667" class="jt362mrmb"/><stop offset="1" class="yfkzyxbts"/></linearGradient><linearGradient id="iFjMXle" x1="21.381" x2="19.771" y1="11.921" y2="11.853" gradientUnits="userSpaceOnUse"><stop offset=".267" class="b-7ftg6nf"/><stop offset="1" class="cd8hmxqwr"/></linearGradient><linearGradient id="iZA9s7c" x1="15.957" x2="15.957" y1="6.369" y2="8.061" gradientUnits="userSpaceOnUse"><stop offset=".19" class="fqdhr8bzz"/><stop offset="1" class="nfknqibuy"/></linearGradient><linearGradient id="iX2ciYc" x1="16.938" x2="15.238" y1="11.676" y2="11.816" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ebnkoj8rz"/><stop offset=".813" class="yr_s1wb-e"/></linearGradient><linearGradient id="iuHhvIb" x1="15.832" x2="15.832" y1="12.847" y2="12.019" gradientUnits="userSpaceOnUse"><stop offset=".072" class="qvn0k1bbh"/><stop offset="1" class="l5lubve6n"/></linearGradient><linearGradient id="iuVEnXF" x1="16" x2="16" y1="9.947" y2="10.591" gradientUnits="userSpaceOnUse"><stop class="xogtr7m2h"/><stop offset="1" class="hzipojmca"/></linearGradient><linearGradient id="int20Xd" x1="18.96" x2="18.646" y1="10.105" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMuXX6c" x1="14.562" x2="14.248" y1="10.105" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9437oe" x1="15.861" x2="14.049" y1="20.654" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="qd6na2-uz"/><stop offset="1" class="syu7jn24l"/></linearGradient><linearGradient id="iPNhVDc" x1="12.129" x2="12.473" y1="7.466" y2="4.091" gradientUnits="userSpaceOnUse"><stop class="q96xbxbcl"/><stop offset="1" class="ffiwsc2ql"/></linearGradient><linearGradient id="itoKL9d" x1="18.654" x2="18.688" y1="7.697" y2="5.316" gradientUnits="userSpaceOnUse"><stop class="abrviqbym"/><stop offset="1" class="mntu2074k"/></linearGradient><linearGradient id="ilaJEee" x1="15.58" x2="17.299" y1="6.407" y2="6.407" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="iHRCiSc" x1="15.644" x2="15.644" y1="7.064" y2="6.407" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="iqWdVTd" x1="15.969" x2="15.969" y1="5.491" y2="6.077" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-elf-medium-light" /></template>
<style>
.a0ve6ibhs {
  stop-color: var(--svg-color--9f6c64, #9F6C64);
}

.a4sfhobbt {
  stop-color: var(--svg-color--d0a56a, #D0A56A);
}

.a6tzm1b6f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.39 9.302c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.a7a1m8boe {
  d: path("M15.706 21.287c.263.221.79.924.79 1.906c0 1.053-.358 1.647-.702 2.06a.115.115 0 0 1-.177 0c-.343-.413-.702-1.007-.702-2.06c0-.982.527-1.685.79-1.906");
}

.abrviqbym {
  stop-color: var(--svg-color--e9c090, #E9C090);
}

.apbgrhb_o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m14.049 18.591l1.562 2.188c.12.125.428.3.703 0");
}

.asqw3jbui {
  stop-color: var(--svg-color--b77c64, #B77C64);
}

.b-7ftg6nf {
  stop-color: var(--svg-color--f0bf99, #F0BF99);
}

.b0havcbgv {
  stop-color: var(--svg-color--dc8d16, #DC8D16);
  stop-opacity: 0;
}

.b4mo-29ij {
  d: path("M8.381 12.88c.735-.625 1.279-1.255 1.368-1.594h4.234v3.281l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.023c-.359-1.281.188-2.11 1.297-2.992");
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.c11fd2rff {
  stop-color: var(--svg-color--995a60, #995A60);
}

.c27hakbuc {
  d: path("M11.65 6.128c-.19.25-.68 1.16-.857 1.557c-.117.184-.073.534-.062.711l.258 5.257c.073 2.122 1.397 3.363 3.409 3.363h3.142c2.033 0 3.317-1.305 3.372-3.35l.28-5.14c.011-.178.031-.79-.086-.974c-.177-.397-.629-1.173-.819-1.424z");
}

.c7ols3oue {
  stop-color: var(--svg-color--c5887b, #C5887B);
}

.c9cv27cck {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.763c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.389-.051");
}

.cap0zjbhu {
  stop-color: var(--svg-color--684a43, #684A43);
}

.cd8hmxqwr {
  stop-color: var(--svg-color--fcc49f, #FCC49F);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr9_z1bft {
  d: path("M10.09 9.373v-.375a2.2 2.2 0 0 0-.18-.711a3 3 0 0 0-.126-.23c-.215-.363-.537-.909-.398-1.864c.157-1.077.802-1.476 1.371-1.83q.082-.05.16-.1c.131-.083.254-.154.37-.222c.418-.244.758-.443 1.13-.98c.477-.688 1.36-1.298 2.423-1.126l.159.03c.506.092.734.134.919.134c.23 0 .56-.05 1.18-.164c1.062-.172 1.945.438 2.421 1.125c.373.538.713.737 1.131.981q.174.1.37.222q.078.05.16.1c.569.354 1.214.753 1.37 1.83c.14.955-.182 1.5-.397 1.864c-.05.086-.095.161-.126.23a2.2 2.2 0 0 0-.18.71v.417c-.286.19-.533.385-.735.566c.02-.465.063-1.215.08-1.451c.023-.336.015-.617-.173-.953c-.086-.154-.288-.423-.478-.675c-.14-.187-.274-.365-.35-.481h-8.554c-.178.273-.57.887-.72 1.156c-.187.336-.195.617-.171.953c.016.227.044.917.062 1.381a6.4 6.4 0 0 0-.718-.537");
}

.cu84zd6ok {
  stop-color: var(--svg-color--cfa286, #CFA286);
}

.cva0eccxo {
  stop-color: var(--svg-color--41393b, #41393B);
}

.cy93w4u1k {
  d: path("M18.979 10.35a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.d1ruefb7x {
  d: path("M21.792 6.64c-.054.825-.365 1.33-.502 1.44c.022-.222-.35-.714-.583-1.02s-.253-.415-.462-.42h-1.19c-.903 0-1.917-.141-2.551-1.086s-.373-1.883 0-2.297s1.074-.54 1.581-.047c.507.492.917.414 1.999.89c1.081.477 1.775 1.508 1.707 2.54");
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.d64kkcbzy {
  stop-color: var(--svg-color--49a1ec, #49A1EC);
  stop-opacity: 0;
}

.da96dzbnj {
  d: path("M11.387 12.016c-.904-1.684-2.446-2.402-3.074-2.56c.598 1.662 1.19 2.452 1.6 2.81c.44.384 1.057.369 1.293.355z");
}

.ddoxxtboo {
  stop-color: var(--svg-color--dea692, #DEA692);
  stop-opacity: 0;
}

.dgp6vzbgz {
  stop-color: var(--svg-color--613528, #613528);
  stop-opacity: 0;
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dkch0db-r {
  stop-color: var(--svg-color--d8a487, #D8A487);
}

.dt3zaebva {
  stop-color: var(--svg-color--3a84e4, #3A84E4);
  stop-opacity: 0;
}

.dye_m7bch {
  stop-color: var(--svg-color--d5a184, #D5A184);
  stop-opacity: 0;
}

.e_avwpn4q {
  d: path("M15.906 4.38a.103.103 0 0 1 .144 0c.269.256.694.87.694 1.701c0 .974-.346 1.524-.679 1.907a.115.115 0 0 1-.174 0c-.332-.383-.678-.933-.678-1.907c0-.83.425-1.445.693-1.702");
}

.e8x8t6m4c {
  stop-color: var(--svg-color--c88d69, #C88D69);
}

.ebnkoj8rz {
  stop-color: var(--svg-color--f5c2a6, #F5C2A6);
}

.ebys0kbgr {
  cx: 13.547px;
  cy: 9.956px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ehc1wgbxk {
  stop-color: var(--svg-color--d8a28e, #D8A28E);
  stop-opacity: 0;
}

.eiyn6rq_o {
  stop-color: var(--svg-color--e6ca98, #E6CA98);
  stop-opacity: 0;
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.ekl-imb0v {
  stop-color: var(--svg-color--ffc737, #FFC737);
  stop-opacity: 0;
}

.f6wdi7zjk {
  stop-color: var(--svg-color--187ed9, #187ED9);
}

.f8if605-f {
  stop-color: var(--svg-color--ae607e, #AE607E);
}

.fdx7kfdrk {
  stop-color: var(--svg-color--e6a78d, #E6A78D);
}

.ffiwsc2ql {
  stop-color: var(--svg-color--e8c994, #E8C994);
  stop-opacity: 0;
}

.fp865pypd {
  stop-color: var(--svg-color--b87f6a, #B87F6A);
}

.fqdhr8bzz {
  stop-color: var(--svg-color--b37768, #B37768);
}

.ft5dv1b6b {
  fill: none;
}

.g3-ejv53j {
  stop-color: var(--svg-color--ca937e, #CA937E);
}

.g34co-bjj {
  stop-color: var(--svg-color--fff1bb, #FFF1BB);
}

.g8_ztm4ee {
  stop-color: var(--svg-color--56b5ff, #56B5FF);
  stop-opacity: 0;
}

.g9gcawu6z {
  stop-color: var(--svg-color--9f6561, #9F6561);
}

.gabhccily {
  stop-color: var(--svg-color--544442, #544442);
  stop-opacity: 0;
}

.gb051imgb {
  stop-color: var(--svg-color--b78174, #B78174);
  stop-opacity: 0;
}

.gbkgrm1fg {
  stop-color: var(--svg-color--b78174, #B78174);
}

.gi4t7_tux {
  stroke: var(--svg-color--9e6a40, #9E6A40);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M12.528 8.305c.217-.171.831-.519 1.662-.418");
}

.gq_evtgpi {
  d: path("M8.473 8.63c1.524.44 2.582 1.437 2.928 1.89l.209 2.95c-.399.018-.94.243-1.934-.466c-1.165-1.042-1.72-2.577-1.999-3.546a.67.67 0 0 1 .135-.615a.64.64 0 0 1 .66-.213");
}

.gr7x_rwbv {
  d: path("M16.274 30.094L7.053 20.5a10.95 10.95 0 0 1 5.854-4.208L26.69 30.094z");
}

.gv9gfeant {
  stop-color: var(--svg-color--aa625c, #AA625C);
  stop-opacity: 0;
}

.gvj3_fmrq {
  stop-color: var(--svg-color--7b5649, #7B5649);
}

.h_v8t2rlx {
  d: path("M14.631 10.362c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.h68lkf1_a {
  fill: var(--svg-color--51b9ff, #51B9FF);
  d: path("M23.088 18.457a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.hd78y1x_x {
  stop-color: var(--svg-color--9e634a, #9E634A);
  stop-opacity: 0;
}

.hii9ovp1o {
  d: path("M10.208 6.64c.056.825.291 1.336.435 1.445c-.024-.221.271-.55.463-.892c.218-.39.406-.548.625-.553c.075 0 .609-.024 1.365 0c1.484.046 1.937-.149 2.601-1.094c.665-.945.44-1.875.05-2.29a1.174 1.174 0 0 0-1.656-.046c-.531.492-.961.414-2.094.89s-1.86 1.508-1.79 2.54");
}

.hpb-k7b_o {
  stop-color: var(--svg-color--6b3f38, #6B3F38);
}

.ht2yhibat {
  stop-color: var(--svg-color--4e7ece, #4E7ECE);
}

.hzipojmca {
  stop-color: var(--svg-color--dea68b, #DEA68B);
  stop-opacity: 0;
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i817agb_c {
  stop-color: var(--svg-color--9777b8, #9777B8);
}

.ik39jqbsn {
  fill: var(--svg-color--3f9ef2, #3F9EF2);
  d: path("M5.071 26.776c0-6.036 4.893-10.928 10.929-10.928s10.929 4.892 10.929 10.928v3.318H5.07z");
}

.ikmt3oi5p {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.467a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.235");
}

.itpb-mb4j {
  stop-color: var(--svg-color--e8af96, #E8AF96);
  stop-opacity: 0;
}

.iy0z3721s {
  stop-color: var(--svg-color--288ce5, #288CE5);
}

.j0iym8bez {
  stop-color: var(--svg-color--ffdbac, #FFDBAC);
  stop-opacity: 0;
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.j9cj5qbuy {
  fill: var(--svg-color--231622, #231622);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.ja41yub3g {
  stop-color: var(--svg-color--d5b08a, #D5B08A);
}

.jcf69bbbv {
  stop-color: var(--svg-color--aa625c, #AA625C);
}

.jia0zn94s {
  stop-color: var(--svg-color--544442, #544442);
}

.jnmw52bvm {
  stop-color: var(--svg-color--f2c192, #F2C192);
  stop-opacity: 0;
}

.jt362mrmb {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.jz8djgftu {
  d: path("M15.988 21.248c.264.22.79.924.79 1.906c0 1.053-.358 1.647-.701 2.06a.115.115 0 0 1-.178 0c-.343-.413-.702-1.007-.702-2.06c0-.982.528-1.685.791-1.906");
}

.k_huevcxk {
  stop-color: var(--svg-color--cfa286, #CFA286);
  stop-opacity: 0;
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k7vxnrb9w {
  stop-color: var(--svg-color--d8a584, #D8A584);
  stop-opacity: 0;
}

.k8f_-10rg {
  stop-color: var(--svg-color--a97e4c, #A97E4C);
}

.kna63ccqu {
  stop-color: var(--svg-color--fffbb9, #FFFBB9);
}

.ktl4e9bya {
  d: path("M18.118 9.763c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.389-.051");
}

.kwgh1rbji {
  stop-color: var(--svg-color--3a7edd, #3A7EDD);
  stop-opacity: 0;
}

.l1kqit9sq {
  stop-color: var(--svg-color--f1c299, #F1C299);
  stop-opacity: 0;
}

.l3hsrn8ob {
  stop-color: var(--svg-color--efc097, #EFC097);
  stop-opacity: 0;
}

.l5lubve6n {
  stop-color: var(--svg-color--e1a991, #E1A991);
  stop-opacity: 0;
}

.lgj7dyo1j {
  stop-color: var(--svg-color--dec492, #DEC492);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj7znd7rs {
  stop-color: var(--svg-color--e2bb85, #E2BB85);
  stop-opacity: 0;
}

.lp4if9b4k {
  stop-color: var(--svg-color--180c11, #180C11);
}

.luxz9w7iu {
  stop-color: var(--svg-color--fffec0, #FFFEC0);
  stop-opacity: 0;
}

.ly3r7ebiq {
  stop-color: var(--svg-color--f6d09d, #F6D09D);
  stop-opacity: 0;
}

.m_u5kn1ph {
  stroke: var(--svg-color--c68d7a, #C68D7A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.264 9.285c.656.281 1.844.836 2.851 2.149");
}

.m2zebkb3b {
  stop-color: var(--svg-color--bda75e, #BDA75E);
}

.m5zytr9kz {
  stroke: var(--svg-color--875132, #875132);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.41 8.305c-.218-.171-.86-.523-1.69-.422");
}

.mcb3mdbmq {
  fill: var(--svg-color--432f32, #432F32);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.mdqyvu4ex {
  stop-color: var(--svg-color--187ed9, #187ED9);
  stop-opacity: 0;
}

.mm4k6y1ti {
  stop-color: var(--svg-color--54adff, #54ADFF);
  stop-opacity: 0;
}

.mntu2074k {
  stop-color: var(--svg-color--e9c090, #E9C090);
  stop-opacity: 0;
}

.mv5v-89yi {
  stop-color: var(--svg-color--1f62c6, #1F62C6);
  stop-opacity: 0;
}

.n7-3g8b6a {
  stop-color: var(--svg-color--519df1, #519DF1);
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.nadkffb-q {
  stop-color: var(--svg-color--56b5ff, #56B5FF);
}

.nd_uzdbib {
  stop-color: var(--svg-color--7f4a45, #7F4A45);
}

.nfknqibuy {
  stop-color: var(--svg-color--c9907d, #C9907D);
  stop-opacity: 0;
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nihdl4b3y {
  fill: var(--svg-color--ffcfa1, #FFCFA1);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.nld201kgm {
  stop-color: var(--svg-color--bd856f, #BD856F);
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nstnghbkd {
  stop-color: var(--svg-color--975a60, #975A60);
  stop-opacity: 0;
}

.nt3ohmb5v {
  stop-color: var(--svg-color--7f452e, #7F452E);
}

.nvp34342a {
  stop-color: var(--svg-color--ebd396, #EBD396);
}

.o20k0cbhd {
  stop-color: var(--svg-color--b87f6a, #B87F6A);
  stop-opacity: 0;
}

.o5llqtbdv {
  stop-color: var(--svg-color--8d625b, #8D625B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofalufbug {
  stop-color: var(--svg-color--120a0c, #120A0C);
  stop-opacity: 0;
}

.oi6nokbyq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.302c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.oq0kvn9yx {
  fill: var(--svg-color--d8a585, #D8A585);
  d: path("M8.381 12.88c.735-.625 1.279-1.255 1.368-1.594h4.234v3.281l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.023c-.359-1.281.188-2.11 1.297-2.992");
}

.p0v6jucue {
  stroke: var(--svg-color--9e6a40, #9E6A40);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.457 8.235c-.218-.171-.86-.524-1.691-.423");
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.p8cmnpbrm {
  stop-color: var(--svg-color--4990e8, #4990E8);
  stop-opacity: 0;
}

.p8z5r2h1v {
  stop-color: var(--svg-color--8a575a, #8A575A);
}

.pa8e75o9n {
  stop-color: var(--svg-color--2d5fc4, #2D5FC4);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
}

.peclnma7n {
  d: path("M20.714 12.383c.904-1.683 2.585-2.677 3.214-2.835c-.599 1.663-1.33 2.727-1.74 3.085c-.44.384-1.057.369-1.293.355z");
}

.pes_lybqy {
  fill: var(--svg-color--dca588, #DCA588);
  d: path("m15.618 10.253l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.pf0n6ab7v {
  stop-color: var(--svg-color--55302a, #55302A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plcv9bbgt {
  stop-color: var(--svg-color--d8a28e, #D8A28E);
}

.pqpxg6gcd {
  fill: var(--svg-color--ffa52a, #FFA52A);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.ps0fa7bxo {
  d: path("M23.088 18.457a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.q439j4sbs {
  stop-color: var(--svg-color--dea692, #DEA692);
}

.q52fr3noq {
  stop-color: var(--svg-color--d59f87, #D59F87);
}

.q8p3q3bqx {
  stop-color: var(--svg-color--be856f, #BE856F);
}

.q96xbxbcl {
  stop-color: var(--svg-color--deaf94, #DEAF94);
}

.qd6na2-uz {
  stop-color: var(--svg-color--b1736a, #B1736A);
}

.qeihuuzsw {
  d: path("M18.184 9.574a.893.893 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

.qfs6aobhn {
  stop-color: var(--svg-color--a85d71, #A85D71);
  stop-opacity: 0;
}

.qfx4f-mat {
  stop-color: var(--svg-color--fff9be, #FFF9BE);
}

.qhrgfk8ap {
  stop-color: var(--svg-color--e6ca98, #E6CA98);
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.qqeozgbom {
  fill: var(--svg-color--f5c2a3, #F5C2A3);
  d: path("M20.955 10.248c.05.083.177.232.289.164c.14-.086.977-1.008 2.438-1.5c.323-.09.467.112.511.26c-.028-.062-.111-.138-.308-.143c-.32-.008-1.938.64-3.352 2.453z");
}

.qttrphznb {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.467a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.qvn0k1bbh {
  stop-color: var(--svg-color--cf8e80, #CF8E80);
}

.qylf6wbub {
  d: path("M8.85 6.407a.53.53 0 0 1 .529-.529h13.18a.53.53 0 0 1 0 1.059H9.378a.53.53 0 0 1-.53-.53");
}

.r-p883bfh {
  stop-color: var(--svg-color--e3b482, #E3B482);
}

.r0z1khbsa {
  stop-color: var(--svg-color--fffec0, #FFFEC0);
}

.r324_0iwv {
  stop-color: var(--svg-color--c8898a, #C8898A);
  stop-opacity: 0;
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.ro__zqilq {
  stop-color: var(--svg-color--fdc49d, #FDC49D);
}

.ro5kwtkrd {
  stop-color: var(--svg-color--824d4f, #824D4F);
  stop-opacity: 0;
}

.s_sn4ab8f {
  fill: var(--svg-color--bc7a76, #BC7A76);
  d: path("m15.447 10.449l-.57 1.838c-.098.378.136.756.467.756h.707c.331 0 .565-.384.468-.756l-.478-1.838c-.102-.408-.487-.408-.594 0");
}

.s1jm76o_g {
  stop-color: var(--svg-color--8b5548, #8B5548);
  stop-opacity: 0;
}

.sd49k712l {
  stop-color: var(--svg-color--d5a184, #D5A184);
}

.sfwupzbpl {
  stop-color: var(--svg-color--ce9578, #CE9578);
  stop-opacity: 0;
}

.si20u1b5q {
  stop-color: var(--svg-color--b67760, #B67760);
}

.sl7vf6bvq {
  stop-color: var(--svg-color--b99c5f, #B99C5F);
}

.smbbml-bd {
  stop-color: var(--svg-color--bd8d6a, #BD8D6A);
}

.sx3rjlbzk {
  stop-color: var(--svg-color--d4a287, #D4A287);
}

.syu7jn24l {
  stop-color: var(--svg-color--b1736a, #B1736A);
  stop-opacity: 0;
}

.t0ficfbbx {
  stop-color: var(--svg-color--ffedb6, #FFEDB6);
  stop-opacity: 0;
}

.t34bfozye {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M16 13.864c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.t60ntu-wj {
  stop-color: var(--svg-color--b47d69, #B47D69);
}

.tal-3wbcb {
  fill: var(--svg-color--e3b293, #E3B293);
  d: path("M23.527 8.63c-1.524.44-2.582 1.437-2.928 1.89l-.21 2.95c.4.018.94.243 1.935-.466c1.164-1.042 1.72-2.577 1.999-3.546a.67.67 0 0 0-.136-.615a.64.64 0 0 0-.66-.213");
}

.te0saggyn {
  stop-color: var(--svg-color--7d4d4c, #7D4D4C);
}

.tk0xf0bde {
  stop-color: var(--svg-color--49a1ec, #49A1EC);
}

.tkhb3b5oc {
  stroke: var(--svg-color--875132, #875132);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.528 8.305c.217-.171.831-.519 1.662-.418");
}

.tp-3hccxn {
  stop-color: var(--svg-color--9777b8, #9777B8);
  stop-opacity: 0;
}

.tvz40gbou {
  stop-color: var(--svg-color--be8471, #BE8471);
  stop-opacity: 0;
}

.u3yytvbgg {
  d: path("M12.12 14.779c-.82-.07-1.718.055-2.327 1.11c-.61.96-.793 3.254 1.914 4.5c1.443.663 3.695.898 4.293.898c.633 0 2.85-.235 4.293-.899c2.707-1.245 2.523-3.539 1.914-4.5c-.61-1.054-1.508-1.18-2.328-1.11l-3.88.14z");
}

.u9m-38uic {
  stop-color: var(--svg-color--4c200c, #4C200C);
}

.u9wqsy2sp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16 13.864c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33Z");
}

.uf8v-8bxn {
  fill: var(--svg-color--459be2, #459BE2);
  d: path("M8.912 18.457a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.uvyahya6g {
  stop-color: var(--svg-color--c28475, #C28475);
  stop-opacity: 0;
}

.vgv3oz8qv {
  stop-color: var(--svg-color--cb997a, #CB997A);
  stop-opacity: 0;
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.vn8pvc5iu {
  stop-color: var(--svg-color--519df1, #519DF1);
  stop-opacity: 0;
}

.vs6qzmbeh {
  stop-color: var(--svg-color--c4897d, #C4897D);
  stop-opacity: 0;
}

.vsbibr_ed {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
}

.vtamvdyqj {
  stop-color: var(--svg-color--c28475, #C28475);
}

.w_rnmcxom {
  stop-color: var(--svg-color--c6907d, #C6907D);
}

.w1ahfsiui {
  stop-color: var(--svg-color--ffedb6, #FFEDB6);
}

.w4q7dg2ti {
  stop-color: var(--svg-color--411d19, #411D19);
}

.wifu-cbwd {
  d: path("M8.912 18.457a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.wjq_rgywi {
  stop-color: var(--svg-color--dec492, #DEC492);
  stop-opacity: 0;
}

.wogh8-v4o {
  stop-color: var(--svg-color--3f70d2, #3F70D2);
}

.wsy42fbgm {
  stop-color: var(--svg-color--ae706a, #AE706A);
}

.wy3jcw9jp {
  stop-color: var(--svg-color--fff9be, #FFF9BE);
  stop-opacity: 0;
}

.wyqd5ab8k {
  stop-color: var(--svg-color--efc097, #EFC097);
}

.xbdij97tt {
  d: path("m15.719 20.408l-2.871-4.067h6.265l-2.863 4.067c-.164.215-.395.2-.531 0");
}

.xfqn-nbow {
  stop-color: var(--svg-color--1f62c6, #1F62C6);
}

.xilj489kn {
  stop-color: var(--svg-color--180c11, #180C11);
  stop-opacity: 0;
}

.xnfwhubut {
  stop-color: var(--svg-color--6f403b, #6F403B);
}

.xogtr7m2h {
  stop-color: var(--svg-color--dea68b, #DEA68B);
}

.xu2rljbva {
  stop-color: var(--svg-color--55302a, #55302A);
  stop-opacity: 0;
}

.y2vknabsu {
  d: path("M13.816 9.574a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.y59bi164p {
  d: path("m15.618 10.253l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.y7tt4qbej {
  stop-color: var(--svg-color--5bb5ff, #5BB5FF);
  stop-opacity: 0;
}

.yap4pcbws {
  stop-color: var(--svg-color--dc8d16, #DC8D16);
}

.ybfplbczy {
  stop-color: var(--svg-color--76c1ff, #76C1FF);
}

.ycfa7kt7e {
  stop-color: var(--svg-color--3a66c5, #3A66C5);
}

.yfkzyxbts {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
  stop-opacity: 0;
}

.yg8va_99z {
  stop-color: var(--svg-color--eddda3, #EDDDA3);
}

.yngnm5bdn {
  stop-color: var(--svg-color--2d5fc4, #2D5FC4);
  stop-opacity: 0;
}

.yr_s1wb-e {
  stop-color: var(--svg-color--f5c2a6, #F5C2A6);
  stop-opacity: 0;
}

.ytmccib4c {
  stop-color: var(--svg-color--b17859, #B17859);
}

.yvvekm_dy {
  stop-color: var(--svg-color--41393b, #41393B);
  stop-opacity: 0;
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.z-thopeux {
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.z77zzmbkv {
  d: path("M5.071 26.776c0-6.036 4.893-10.928 10.929-10.928s10.929 4.892 10.929 10.928v3.318H5.07z");
}

.zeavlp0uo {
  stop-color: var(--svg-color--edc595, #EDC595);
  stop-opacity: 0;
}

.zhwrqyb9y {
  d: path("M20.612 12.016c.905-1.684 2.446-2.402 3.075-2.56c-.598 1.662-1.19 2.452-1.6 2.81c-.44.384-1.057.369-1.294.355z");
}

.zmahyob7y {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
  stop-opacity: 0;
}

.zsyl6jyid {
  stop-color: var(--svg-color--c38e78, #C38E78);
  stop-opacity: 0;
}

.zy43xh0vl {
  cx: 13.547px;
  cy: 9.956px;
  rx: 0.39px;
  ry: 0.197px;
}

</style>
