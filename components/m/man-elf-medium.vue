<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1uVkFd)"><path class="pqpxg6gcd"/><path fill="url(#iUhI09c)" class="z-thopeux"/><path fill="url(#ihWU4vd)" class="z-thopeux"/></g><g filter="url(#iVvrBke)"><path class="j9cj5qbuy"/><path fill="url(#iz6GOIb)" class="z-thopeux"/><path fill="url(#iOivUbb)" class="z-thopeux"/></g><g filter="url(#i0Mdure)"><path class="mcb3mdbmq"/><path fill="url(#ibuxX9V)" class="z-thopeux"/></g><path fill="url(#iyAMjye)" class="z-thopeux"/><g filter="url(#iDIyUtb)"><path class="kjw2dcsze"/><path fill="url(#igjR5De)" class="b4mo-29ij"/><path fill="url(#iJwxMPe)" class="b4mo-29ij"/></g><path class="ik39jqbsn"/><path fill="url(#iTsW5Nc)" class="z77zzmbkv"/><path fill="url(#iQcA7En)" class="z77zzmbkv"/><path fill="url(#iOfjqcd)" class="z77zzmbkv"/><path fill="url(#isgVVHd)" class="z77zzmbkv"/><path fill="url(#ibiEGBb)" class="z77zzmbkv"/><path class="uf8v-8bxn"/><path fill="url(#iP6UBmc)" class="wifu-cbwd"/><path fill="url(#ihNLNpd)" class="wifu-cbwd"/><path fill="url(#iER4OWb)" class="wifu-cbwd"/><path class="h68lkf1_a"/><path fill="url(#izBzNGe)" class="ps0fa7bxo"/><path fill="url(#ie411je)" class="ps0fa7bxo"/><path fill="url(#i8cymIQ)" class="ps0fa7bxo"/><path fill="url(#i8aYqre)" class="gr7x_rwbv"/><path fill="url(#iUn8IAz)" class="gr7x_rwbv"/><path fill="url(#iTXMv8b)" class="gr7x_rwbv"/><path fill="url(#ixwetQd)" class="gr7x_rwbv"/><path fill="url(#iLSaoWb)" class="gr7x_rwbv"/><path fill="url(#i5Lj3Yc)" class="gr7x_rwbv"/><path fill="url(#i82dLZi)" class="gr7x_rwbv"/><g filter="url(#iazwyzM)"><path fill="url(#i2yDo0c)" class="a7a1m8boe"/></g><g filter="url(#iQcM27c)"><path fill="url(#ivXyFxp)" class="jz8djgftu"/></g><g filter="url(#igf1Dhd)"><path fill="url(#iCWbHoe)" class="u3yytvbgg"/><path fill="url(#iuKX0Uc)" class="u3yytvbgg"/><path fill="url(#i6bZPzd)" class="u3yytvbgg"/><path fill="url(#icEs3vd)" class="u3yytvbgg"/><path fill="url(#iAGCnhe)" class="u3yytvbgg"/></g><path fill="url(#i7UblNe)" class="xbdij97tt"/><path fill="url(#i3P7WEb)" class="xbdij97tt"/><path fill="url(#iP18dcb)" class="xbdij97tt"/><path fill="url(#izzV4bb)" class="xbdij97tt"/><path fill="url(#iBBvBDe)" class="xbdij97tt"/><g filter="url(#iEZFC3d)"><path class="vufvhcc4w"/></g><g filter="url(#i6D3eNL)"><path fill="url(#iY3Kj6b)" class="gq_evtgpi"/><path fill="url(#iRWNCOc)" class="gq_evtgpi"/></g><g filter="url(#iw5oJRc)"><path fill="url(#iQevAfc)" class="peclnma7n"/></g><g filter="url(#iU1stER)"><path fill="url(#idc8Reb)" class="zhwrqyb9y"/><path fill="url(#izC8BBe)" class="zhwrqyb9y"/></g><path fill="url(#iKoOITb)" class="da96dzbnj"/><path fill="url(#iI5yFKb)" class="da96dzbnj"/><g filter="url(#iFvgpWd)"><path class="ds-desbdp"/></g><g filter="url(#iqAU4Jd)"><path fill="url(#iwwn05b)" class="c27hakbuc"/><path fill="url(#iSYTsCd)" class="c27hakbuc"/><path fill="url(#iOgJhmc)" class="c27hakbuc"/><path fill="url(#ihuO6Ud)" class="c27hakbuc"/><path fill="url(#iToZRAc)" class="c27hakbuc"/><path fill="url(#izc7Die)" class="c27hakbuc"/></g><path fill="url(#iIgQ5Xc)" class="c27hakbuc"/><path fill="url(#iVF6ISc)" class="c27hakbuc"/><g filter="url(#ipPBk8c)"><path class="yw13e1b2z"/></g><path class="bkoaoh_fj"/><path fill="url(#i9zgZ4b)" class="y59bi164p"/><path fill="url(#iiIcmWb)" class="y59bi164p"/><g filter="url(#ibUzZMv)"><path stroke="url(#ihPVwxb)" class="u9wqsy2sp"/></g><path class="px2yrv1tc"/><path class="a6tzm1b6f"/><path fill="url(#iP8FdEd)" class="qeihuuzsw"/><path class="qttrphznb"/><g filter="url(#iGL6NEb)"><path class="c9cv27cck"/><path fill="url(#iszcHob)" class="ktl4e9bya"/></g><g filter="url(#iQ1qcfe)"><path fill="url(#int20Xd)" class="cy93w4u1k"/></g><path class="oi6nokbyq"/><path fill="url(#ilstd7d)" class="y2vknabsu"/><path class="ikmt3oi5p"/><g filter="url(#iW86i0b)"><path fill="url(#iMuXX6c)" class="h_v8t2rlx"/></g><g filter="url(#ioJFhPQ)"><ellipse transform="rotate(-27.914 13.547 9.956)" class="ebys0kbgr"/><ellipse fill="url(#igxaqOe)" transform="rotate(-27.914 13.547 9.956)" class="zy43xh0vl"/></g><g filter="url(#imleR9b)"><path stroke="url(#i9437oe)" class="apbgrhb_o"/></g><g filter="url(#ijcKt0d)"><path class="u_90aebfc"/></g><g filter="url(#ia1tddb)"><path class="bxp1aya8n"/></g><g filter="url(#i2dTi4b)"><path class="z51dcdcri"/></g><g filter="url(#ifxZY3b)"><path class="ror6akb6y"/></g><path fill="url(#iHTdHCc)" class="cr9_z1bft"/><path fill="url(#i6nMw7d)" class="cr9_z1bft"/><path fill="url(#iX1m9sd)" class="cr9_z1bft"/><path fill="url(#i4hKgZb)" class="cr9_z1bft"/><g filter="url(#i30TiQd)"><path fill="url(#il5VIwM)" class="hii9ovp1o"/><path fill="url(#isRS9Zb)" class="hii9ovp1o"/></g><g filter="url(#ij3WpBp)"><path fill="url(#i4ctgyh)" class="d1ruefb7x"/><path fill="url(#itTR4Kd)" class="d1ruefb7x"/></g><path fill="url(#ilaJEee)" class="qylf6wbub"/><path fill="url(#iHRCiSc)" class="qylf6wbub"/><path fill="url(#iqWdVTd)" class="qylf6wbub"/><path fill="url(#imnlytb)" class="qylf6wbub"/><path fill="url(#i4PCG6d)" class="qylf6wbub"/><path fill="url(#iQPybpd)" class="qylf6wbub"/><path fill="url(#iRJILpP)" class="e_avwpn4q"/><defs><radialGradient id="iUhI09c" cx="0" cy="0" r="1" gradientTransform="rotate(119.999 8.37 12.873)scale(3.50014 9.06684)" gradientUnits="userSpaceOnUse"><stop class="jtnx86cjw"/><stop offset="1" class="ekl-imb0v"/></radialGradient><radialGradient id="ihWU4vd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="yap4pcbws"/><stop offset="1" class="b0havcbgv"/></radialGradient><radialGradient id="iz6GOIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="cva0eccxo"/><stop offset="1" class="yvvekm_dy"/></radialGradient><radialGradient id="iOivUbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="lp4if9b4k"/><stop offset="1" class="ofalufbug"/><stop offset="1" class="xilj489kn"/></radialGradient><radialGradient id="ibuxX9V" cx="0" cy="0" r="1" gradientTransform="rotate(134.256 9.246 11.762)scale(1.70162 4.86497)" gradientUnits="userSpaceOnUse"><stop class="jia0zn94s"/><stop offset="1" class="gabhccily"/></radialGradient><radialGradient id="iyAMjye" cx="0" cy="0" r="1" gradientTransform="matrix(.125 4.43137 -7.06927 .19941 22.436 13.66)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="ab_2_bcns"/><stop offset="1" class="l6ku6_bey"/></radialGradient><radialGradient id="igjR5De" cx="0" cy="0" r="1" gradientTransform="rotate(-98.799 12.543 4.647)scale(3.20061 3.97853)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="nagianp2z"/><stop offset="1" class="c7ltk09yg"/></radialGradient><radialGradient id="iJwxMPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39063 .57888 -1.52227 -6.28657 12.111 14.59)" gradientUnits="userSpaceOnUse"><stop class="ok95vkw1c"/><stop offset="1" class="k8vvgib0z"/></radialGradient><radialGradient id="iQcA7En" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -11.6596 23.142 20.841)" gradientUnits="userSpaceOnUse"><stop class="nadkffb-q"/><stop offset="1" class="g8_ztm4ee"/></radialGradient><radialGradient id="iOfjqcd" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.531 5.262)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="n7-3g8b6a"/><stop offset="1" class="vn8pvc5iu"/></radialGradient><radialGradient id="isgVVHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51484 .49425 -5.62821 -5.8627 15.745 29.022)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="pa8e75o9n"/><stop offset="1" class="yngnm5bdn"/></radialGradient><radialGradient id="iP6UBmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 30.094)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="xfqn-nbow"/><stop offset="1" class="mv5v-89yi"/></radialGradient><radialGradient id="ihNLNpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.216)" gradientUnits="userSpaceOnUse"><stop class="tk0xf0bde"/><stop offset="1" class="d64kkcbzy"/></radialGradient><radialGradient id="izBzNGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.71323 -.26753 25.58 28.529)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="ybfplbczy"/><stop offset="1" class="y7tt4qbej"/></radialGradient><radialGradient id="i8cymIQ" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.623)" gradientUnits="userSpaceOnUse"><stop class="f6wdi7zjk"/><stop offset="1" class="mdqyvu4ex"/></radialGradient><radialGradient id="iTXMv8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.43994 -1.46875 8.18973 8.02909 15.736 29.935)" gradientUnits="userSpaceOnUse"><stop class="c11fd2rff"/><stop offset="1" class="qfs6aobhn"/></radialGradient><radialGradient id="ixwetQd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.282 11.452)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="iLSaoWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.31)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="w4q7dg2ti"/><stop offset="1" class="ro5kwtkrd"/></radialGradient><radialGradient id="i2yDo0c" cx="0" cy="0" r="1" gradientTransform="rotate(97.64 -1.695 18.198)scale(3.08805 1.1998)" gradientUnits="userSpaceOnUse"><stop class="xnfwhubut"/><stop offset="1" class="nd_uzdbib"/></radialGradient><radialGradient id="ivXyFxp" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.685)" gradientUnits="userSpaceOnUse"><stop class="kna63ccqu"/><stop offset="1" class="yg8va_99z"/></radialGradient><radialGradient id="iCWbHoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.22354 13.8281 0 16 21.287)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="g9gcawu6z"/><stop offset="1" class="hpb-k7b_o"/></radialGradient><radialGradient id="iuKX0Uc" cx="0" cy="0" r="1" gradientTransform="rotate(153.453 7.604 9.74)scale(9.41646 14.488)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="ngc6h6bst"/><stop offset="1" class="o5llqtbdv"/></radialGradient><radialGradient id="i6bZPzd" cx="0" cy="0" r="1" gradientTransform="matrix(6.05257 5.9867 -7.0398 7.11726 14.455 14.53)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="s1jm76o_g"/><stop offset="1" class="a0ve6ibhs"/></radialGradient><radialGradient id="icEs3vd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.94665 -1.47583 .92553 -2.47504 13.644 16.072)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="u9m-38uic"/><stop offset="1" class="dgp6vzbgz"/></radialGradient><radialGradient id="iAGCnhe" cx="0" cy="0" r="1" gradientTransform="rotate(120.992 5.816 12.626)scale(7.05716 2.39887)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="pf0n6ab7v"/><stop offset="1" class="xu2rljbva"/></radialGradient><radialGradient id="i7UblNe" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -4.22173 2.03479 1.08445 16.142 20.563)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="jtzs6yb4f"/><stop offset="1" class="zvqo526_s"/></radialGradient><radialGradient id="iP18dcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.31863 -6.86348 0 15.98 16.654)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="gpe4-y8bv"/><stop offset="1" class="gsx7qrx_x"/></radialGradient><radialGradient id="izzV4bb" cx="0" cy="0" r="1" gradientTransform="rotate(42.523 -14.575 24.68)scale(3.58325 2.63576)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="em0cv-ghg"/><stop offset="1" class="kypsv4bum"/></radialGradient><radialGradient id="iY3Kj6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.4697 -1.59165 3.40232 3.14166 8.65 11.062)" gradientUnits="userSpaceOnUse"><stop class="iq2da-til"/><stop offset="1" class="csq4jn2kx"/></radialGradient><radialGradient id="iRWNCOc" cx="0" cy="0" r="1" gradientTransform="rotate(71.741 -1.116 10.387)scale(5.60855 3.99461)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="xego_hb4f"/><stop offset="1" class="dctelizww"/></radialGradient><radialGradient id="idc8Reb" cx="0" cy="0" r="1" gradientTransform="matrix(2.96202 -3.23123 2.01258 1.8449 21.26 12.388)" gradientUnits="userSpaceOnUse"><stop class="k-y9l9pil"/><stop offset="1" class="jaylb0qns"/></radialGradient><radialGradient id="izC8BBe" cx="0" cy="0" r="1" gradientTransform="rotate(-143.457 13.415 2.046)scale(1.81797 6.41679)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="rs9lecbmb"/><stop offset="1" class="jpl5qbbcg"/></radialGradient><radialGradient id="iKoOITb" cx="0" cy="0" r="1" gradientTransform="rotate(-143.844 7.348 4.223)scale(3.06704 1.99268)" gradientUnits="userSpaceOnUse"><stop class="djzk18uun"/><stop offset="1" class="omu6ddcev"/></radialGradient><radialGradient id="iI5yFKb" cx="0" cy="0" r="1" gradientTransform="matrix(1.14395 -1.05015 3.68181 4.01068 9.339 11.612)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="rlf5pscxx"/><stop offset="1" class="u_dvqebgf"/></radialGradient><radialGradient id="iwwn05b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.89643 0 0 -9.1676 19.459 11.572)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="omgobwb-x"/><stop offset=".659" class="yuhnzydjs"/></radialGradient><radialGradient id="iSYTsCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.375 1.53869 0 13.467 9.473)" gradientUnits="userSpaceOnUse"><stop class="sl-oxubgm"/><stop offset="1" class="ylyop8bmx"/></radialGradient><radialGradient id="iOgJhmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53125 1.85279 0 18.404 9.504)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="o-suhjrka"/><stop offset="1" class="gmx9pbbfo"/></radialGradient><radialGradient id="ihuO6Ud" cx="0" cy="0" r="1" gradientTransform="rotate(121.203 6.897 8.81)scale(2.45067 1.84691)" gradientUnits="userSpaceOnUse"><stop class="xakt0cbhn"/><stop offset="1" class="fl5l0ebky"/></radialGradient><radialGradient id="iToZRAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.05286 1.21803 -1.64625 1.423 14.537 6.935)" gradientUnits="userSpaceOnUse"><stop class="anahn0m5t"/><stop offset="1" class="phiaf5bvz"/></radialGradient><radialGradient id="iIgQ5Xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.86294 -9.33408 0 15.957 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="ehm-d5v2e"/><stop offset="1" class="e7-1amrmf"/></radialGradient><radialGradient id="ihPVwxb" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 -.625 1.875 .98437 14.614 14.31)" gradientUnits="userSpaceOnUse"><stop class="gsq_6nbql"/><stop offset="1" class="bg7kyoqvj"/></radialGradient><radialGradient id="iP8FdEd" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 6.732 9.582)scale(1.10543 1.21398)" gradientUnits="userSpaceOnUse"><stop class="gvj3_fmrq"/><stop offset="1" class="cap0zjbhu"/></radialGradient><radialGradient id="iszcHob" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.459 .671)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilstd7d" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.55 8.513)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="gvj3_fmrq"/><stop offset="1" class="cap0zjbhu"/></radialGradient><radialGradient id="igxaqOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.53 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHTdHCc" cx="0" cy="0" r="1" gradientTransform="rotate(117.277 8.224 7.024)scale(5.59037 9.77256)" gradientUnits="userSpaceOnUse"><stop class="zyyeecb5g"/><stop offset="1" class="xvr3ve97x"/></radialGradient><radialGradient id="i6nMw7d" cx="0" cy="0" r="1" gradientTransform="rotate(132.745 9.428 6.296)scale(1.40425 2.67046)" gradientUnits="userSpaceOnUse"><stop class="rz3uprbtw"/><stop offset="1" class="m2odj8bqk"/></radialGradient><radialGradient id="iX1m9sd" cx="0" cy="0" r="1" gradientTransform="rotate(109.616 4.569 5.918)scale(4.28106 1.6355)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="bk_mrebvc"/><stop offset="1" class="ajacucc-u"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i4hKgZb" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -2.34375 5.5017 5.28165 10.467 9.535)" gradientUnits="userSpaceOnUse"><stop class="fgtmagb3c"/><stop offset="1" class="pyuxo8yyq"/></radialGradient><radialGradient id="il5VIwM" cx="0" cy="0" r="1" gradientTransform="rotate(133.821 6.841 4.913)scale(5.37073 3.4468)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="la5p1obbs"/><stop offset="1" class="gk4xvzbnm"/></radialGradient><radialGradient id="isRS9Zb" cx="0" cy="0" r="1" gradientTransform="rotate(170.894 7.88 2.91)scale(1.57972 2.4034)" gradientUnits="userSpaceOnUse"><stop offset=".299" class="m7dikjbkp"/><stop offset="1" class="k2m8gob9n"/></radialGradient><radialGradient id="i4ctgyh" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 .70011 -.22482 .98345 19.717 4.785)" gradientUnits="userSpaceOnUse"><stop class="lnclpfbdm"/><stop offset="1" class="mcpkokbsm"/></radialGradient><radialGradient id="itTR4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.80875 2.45558 -2.78933 -3.1905 19.596 3.83)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="i27uqaf5z"/><stop offset="1" class="fjn_sgtjy"/></radialGradient><radialGradient id="imnlytb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.767 6.234)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="i4PCG6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 5.702)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iQPybpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.228 5.921)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="iRJILpP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.978 7.5)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><filter id="i1uVkFd" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.827451 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.807843 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1371" result="effect2_innerShadow_4002_1371"/></filter><filter id="iVvrBke" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.219608 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.215686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1371" result="effect2_innerShadow_4002_1371"/></filter><filter id="i0Mdure" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.270588 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.282353 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1371" result="effect2_innerShadow_4002_1371"/></filter><filter id="iDIyUtb" width="7.258" height="6.609" x="6.975" y="11.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.215686 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="iazwyzM" width="2.581" height="5.008" x="14.415" y="20.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".25"/></filter><filter id="iQcM27c" width="1.681" height="4.108" x="15.197" y="21.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="igf1Dhd" width="13.169" height="6.924" x="9.415" y="14.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="iEZFC3d" width="4.058" height="5.011" x="20.39" y="8.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.352941 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="i6D3eNL" width="3.958" height="5.111" x="7.652" y="8.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.290196 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="iw5oJRc" width="3.614" height="3.845" x="20.514" y="9.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".1"/></filter><filter id="iU1stER" width="3.274" height="3.37" x="20.512" y="9.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".05"/></filter><filter id="iFvgpWd" width="4.072" height="2.992" x="20.333" y="8.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".1"/></filter><filter id="iqAU4Jd" width="10.987" height="10.888" x="10.713" y="6.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.443137 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="ipPBk8c" width="3.187" height="4.4" x="14.104" y="9.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".375"/></filter><filter id="ibUzZMv" width="3.668" height="1.523" x="14.166" y="13.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".075"/></filter><filter id="iGL6NEb" width=".787" height=".696" x="17.448" y="9.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".05"/></filter><filter id="iQ1qcfe" width=".891" height=".913" x="18.287" y="9.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".1"/></filter><filter id="iW86i0b" width=".986" height="1.04" x="13.845" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".1"/></filter><filter id="ioJFhPQ" width=".913" height=".705" x="13.09" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".05"/></filter><filter id="imleR9b" width="2.916" height="3.003" x="13.723" y="18.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".125"/></filter><filter id="ijcKt0d" width="2.863" height="1.636" x="12.052" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0784314 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="ia1tddb" width="2.563" height="1.336" x="12.078" y="7.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".15"/></filter><filter id="i2dTi4b" width="2.891" height="1.641" x="17.244" y="7.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0784314 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1371"/></filter><filter id="ifxZY3b" width="2.591" height="1.341" x="17.316" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".15"/></filter><filter id="i30TiQd" width="6.417" height="5.694" x="9.953" y="2.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".125"/></filter><filter id="ij3WpBp" width="6.176" height="5.689" x="15.87" y="2.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1371" stdDeviation=".125"/></filter><linearGradient id="iTsW5Nc" x1="15.049" x2="15.049" y1="30.094" y2="20.685" gradientUnits="userSpaceOnUse"><stop offset=".04" class="wogh8-v4o"/><stop offset="1" class="dt3zaebva"/></linearGradient><linearGradient id="ibiEGBb" x1="23.291" x2="22.822" y1="26.669" y2="26.669" gradientUnits="userSpaceOnUse"><stop offset=".327" class="iy0z3721s"/><stop offset="1" class="mm4k6y1ti"/></linearGradient><linearGradient id="iER4OWb" x1="8.912" x2="8.912" y1="30.094" y2="21.279" gradientUnits="userSpaceOnUse"><stop class="ycfa7kt7e"/><stop offset="1" class="kwgh1rbji"/></linearGradient><linearGradient id="ie411je" x1="24.142" x2="26.611" y1="29.466" y2="21.56" gradientUnits="userSpaceOnUse"><stop offset=".116" class="ht2yhibat"/><stop offset="1" class="p8cmnpbrm"/></linearGradient><linearGradient id="i8aYqre" x1="12.517" x2="22.705" y1="21.435" y2="31.091" gradientUnits="userSpaceOnUse"><stop class="te0saggyn"/><stop offset="1" class="wsy42fbgm"/></linearGradient><linearGradient id="iUn8IAz" x1="26.895" x2="21.238" y1="31.06" y2="26.873" gradientUnits="userSpaceOnUse"><stop class="gbkgrm1fg"/><stop offset="1" class="gb051imgb"/></linearGradient><linearGradient id="i5Lj3Yc" x1="15.015" x2="15.229" y1="28.829" y2="28.625" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="nstnghbkd"/></linearGradient><linearGradient id="i82dLZi" x1="19.002" x2="18.65" y1="22.138" y2="22.498" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="i3P7WEb" x1="15.098" x2="15.695" y1="19.848" y2="19.445" gradientUnits="userSpaceOnUse"><stop offset=".184" class="w0eep96zc"/><stop offset="1" class="glc3rybfi"/></linearGradient><linearGradient id="iBBvBDe" x1="17.642" x2="16.895" y1="18.748" y2="18.373" gradientUnits="userSpaceOnUse"><stop class="r2qtdocxn"/><stop offset="1" class="dfou126rr"/></linearGradient><linearGradient id="iQevAfc" x1="21.817" x2="23.407" y1="12.441" y2="9.413" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b58fw2buv"/><stop offset="1" class="e61suo9cm"/></linearGradient><linearGradient id="izc7Die" x1="21.381" x2="19.771" y1="11.921" y2="11.853" gradientUnits="userSpaceOnUse"><stop offset=".267" class="y6psmgb7b"/><stop offset="1" class="lyakdlbrr"/></linearGradient><linearGradient id="iVF6ISc" x1="15.957" x2="15.957" y1="6.128" y2="8.754" gradientUnits="userSpaceOnUse"><stop class="uw0v2gb2x"/><stop offset="1" class="ln_tzqbjg"/></linearGradient><linearGradient id="i9zgZ4b" x1="16.939" x2="15.707" y1="11.619" y2="11.81" gradientUnits="userSpaceOnUse"><stop offset=".117" class="eoln25m9c"/><stop offset=".685" class="y5vxbvl2m"/></linearGradient><linearGradient id="iiIcmWb" x1="15.832" x2="15.832" y1="12.847" y2="12.224" gradientUnits="userSpaceOnUse"><stop offset=".072" class="h2gz6r_ar"/><stop offset="1" class="x8yee1qkm"/></linearGradient><linearGradient id="int20Xd" x1="18.96" x2="18.646" y1="10.105" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMuXX6c" x1="14.562" x2="14.248" y1="10.105" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9437oe" x1="15.861" x2="14.049" y1="20.654" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="qd6na2-uz"/><stop offset="1" class="syu7jn24l"/></linearGradient><linearGradient id="ilaJEee" x1="15.58" x2="17.299" y1="6.407" y2="6.407" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="iHRCiSc" x1="15.644" x2="15.644" y1="7.064" y2="6.407" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="iqWdVTd" x1="15.969" x2="15.969" y1="5.491" y2="6.077" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-elf-medium" /></template>
<style>
.a0ve6ibhs {
  stop-color: var(--svg-color--9f6c64, #9F6C64);
}

.a6tzm1b6f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.39 9.302c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.a7a1m8boe {
  d: path("M15.706 21.287c.263.221.79.924.79 1.906c0 1.053-.358 1.647-.702 2.06a.115.115 0 0 1-.177 0c-.343-.413-.702-1.007-.702-2.06c0-.982.527-1.685.79-1.906");
}

.ab_2_bcns {
  stop-color: var(--svg-color--27263f, #27263F);
  stop-opacity: 0;
}

.ajacucc-u {
  stop-color: var(--svg-color--453e3f, #453E3F);
  stop-opacity: 0;
}

.anahn0m5t {
  stop-color: var(--svg-color--784f55, #784F55);
}

.apbgrhb_o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m14.049 18.591l1.562 2.188c.12.125.428.3.703 0");
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

.b58fw2buv {
  stop-color: var(--svg-color--c4a38b, #C4A38B);
}

.bg7kyoqvj {
  stop-color: var(--svg-color--a78078, #A78078);
  stop-opacity: 0;
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkoaoh_fj {
  fill: var(--svg-color--94715d, #94715D);
  d: path("m15.618 10.253l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.bxp1aya8n {
  stroke: var(--svg-color--443a3b, #443A3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M12.528 8.305c.217-.171.831-.519 1.662-.418");
}

.c11fd2rff {
  stop-color: var(--svg-color--995a60, #995A60);
}

.c27hakbuc {
  d: path("M11.65 6.128c-.19.25-.68 1.16-.857 1.557c-.117.184-.073.534-.062.711l.258 5.257c.073 2.122 1.397 3.363 3.409 3.363h3.142c2.033 0 3.317-1.305 3.372-3.35l.28-5.14c.011-.178.031-.79-.086-.974c-.177-.397-.629-1.173-.819-1.424z");
}

.c7ltk09yg {
  stop-color: var(--svg-color--151f0e, #151F0E);
  stop-opacity: 0;
}

.c9cv27cck {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.763c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.389-.051");
}

.cap0zjbhu {
  stop-color: var(--svg-color--684a43, #684A43);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr9_z1bft {
  d: path("M10.09 9.373v-.375a2.2 2.2 0 0 0-.18-.711a3 3 0 0 0-.126-.23c-.215-.363-.537-.909-.398-1.864c.157-1.077.802-1.476 1.371-1.83q.082-.05.16-.1c.131-.083.254-.154.37-.222c.418-.244.758-.443 1.13-.98c.477-.688 1.36-1.298 2.423-1.126l.159.03c.506.092.734.134.919.134c.23 0 .56-.05 1.18-.164c1.062-.172 1.945.438 2.421 1.125c.373.538.713.737 1.131.981q.174.1.37.222q.078.05.16.1c.569.354 1.214.753 1.37 1.83c.14.955-.182 1.5-.397 1.864c-.05.086-.095.161-.126.23a2.2 2.2 0 0 0-.18.71v.417c-.286.19-.533.385-.735.566c.02-.465.063-1.215.08-1.451c.023-.336.015-.617-.173-.953c-.086-.154-.288-.423-.478-.675c-.14-.187-.274-.365-.35-.481h-8.554c-.178.273-.57.887-.72 1.156c-.187.336-.195.617-.171.953c.016.227.044.917.062 1.381a6.4 6.4 0 0 0-.718-.537");
}

.csq4jn2kx {
  stop-color: var(--svg-color--89635d, #89635D);
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

.dctelizww {
  stop-color: var(--svg-color--7c5055, #7C5055);
}

.dfou126rr {
  stop-color: var(--svg-color--815643, #815643);
  stop-opacity: 0;
}

.dgp6vzbgz {
  stop-color: var(--svg-color--613528, #613528);
  stop-opacity: 0;
}

.djzk18uun {
  stop-color: var(--svg-color--7d5c5a, #7D5C5A);
}

.ds-desbdp {
  fill: var(--svg-color--c09d84, #C09D84);
  d: path("M20.955 10.248c.05.083.177.232.289.164c.14-.086.977-1.008 2.438-1.5c.323-.09.467.112.511.26c-.028-.062-.111-.138-.308-.143c-.32-.008-1.938.64-3.352 2.453z");
}

.dt3zaebva {
  stop-color: var(--svg-color--3a84e4, #3A84E4);
  stop-opacity: 0;
}

.e_avwpn4q {
  d: path("M15.906 4.38a.103.103 0 0 1 .144 0c.269.256.694.87.694 1.701c0 .974-.346 1.524-.679 1.907a.115.115 0 0 1-.174 0c-.332-.383-.678-.933-.678-1.907c0-.83.425-1.445.693-1.702");
}

.e61suo9cm {
  stop-color: var(--svg-color--c4a38b, #C4A38B);
  stop-opacity: 0;
}

.e7-1amrmf {
  stop-color: var(--svg-color--77415c, #77415C);
}

.ebys0kbgr {
  cx: 13.547px;
  cy: 9.956px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ehm-d5v2e {
  stop-color: var(--svg-color--865d5d, #865D5D);
  stop-opacity: 0;
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.ekl-imb0v {
  stop-color: var(--svg-color--ffc737, #FFC737);
  stop-opacity: 0;
}

.em0cv-ghg {
  stop-color: var(--svg-color--432824, #432824);
}

.eoln25m9c {
  stop-color: var(--svg-color--c19e86, #C19E86);
}

.f6wdi7zjk {
  stop-color: var(--svg-color--187ed9, #187ED9);
}

.fgtmagb3c {
  stop-color: var(--svg-color--281a18, #281A18);
}

.fjn_sgtjy {
  stop-color: var(--svg-color--321c1c, #321C1C);
}

.fl5l0ebky {
  stop-color: var(--svg-color--ad857a, #AD857A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
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

.gk4xvzbnm {
  stop-color: var(--svg-color--331a24, #331A24);
}

.glc3rybfi {
  stop-color: var(--svg-color--a57a6b, #A57A6B);
  stop-opacity: 0;
}

.gmx9pbbfo {
  stop-color: var(--svg-color--a17666, #A17666);
  stop-opacity: 0;
}

.gpe4-y8bv {
  stop-color: var(--svg-color--6c413d, #6C413D);
}

.gq_evtgpi {
  d: path("M8.473 8.63c1.524.44 2.582 1.437 2.928 1.89l.209 2.95c-.399.018-.94.243-1.934-.466c-1.165-1.042-1.72-2.577-1.999-3.546a.67.67 0 0 1 .135-.615a.64.64 0 0 1 .66-.213");
}

.gr7x_rwbv {
  d: path("M16.274 30.094L7.053 20.5a10.95 10.95 0 0 1 5.854-4.208L26.69 30.094z");
}

.gsq_6nbql {
  stop-color: var(--svg-color--a78078, #A78078);
}

.gsx7qrx_x {
  stop-color: var(--svg-color--6c413d, #6C413D);
  stop-opacity: 0;
}

.gvj3_fmrq {
  stop-color: var(--svg-color--7b5649, #7B5649);
}

.h_v8t2rlx {
  d: path("M14.631 10.362c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.h2gz6r_ar {
  stop-color: var(--svg-color--865659, #865659);
}

.h68lkf1_a {
  fill: var(--svg-color--51b9ff, #51B9FF);
  d: path("M23.088 18.457a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
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

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i27uqaf5z {
  stop-color: var(--svg-color--4a302f, #4A302F);
  stop-opacity: 0;
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

.iq2da-til {
  stop-color: var(--svg-color--765550, #765550);
}

.iy0z3721s {
  stop-color: var(--svg-color--288ce5, #288CE5);
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.j9cj5qbuy {
  fill: var(--svg-color--231622, #231622);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.jaylb0qns {
  stop-color: var(--svg-color--ae8a7a, #AE8A7A);
}

.jia0zn94s {
  stop-color: var(--svg-color--544442, #544442);
}

.jpl5qbbcg {
  stop-color: var(--svg-color--a57c6c, #A57C6C);
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.jtzs6yb4f {
  stop-color: var(--svg-color--a87d6d, #A87D6D);
}

.jz8djgftu {
  d: path("M15.988 21.248c.264.22.79.924.79 1.906c0 1.053-.358 1.647-.701 2.06a.115.115 0 0 1-.178 0c-.343-.413-.702-1.007-.702-2.06c0-.982.528-1.685.791-1.906");
}

.k-y9l9pil {
  stop-color: var(--svg-color--b18e7b, #B18E7B);
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k2m8gob9n {
  stop-color: var(--svg-color--6b4e4c, #6B4E4C);
  stop-opacity: 0;
}

.k8vvgib0z {
  stop-color: var(--svg-color--160e18, #160E18);
  stop-opacity: 0;
}

.kjw2dcsze {
  fill: var(--svg-color--281821, #281821);
  d: path("M8.381 12.88c.735-.625 1.279-1.255 1.368-1.594h4.234v3.281l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.023c-.359-1.281.188-2.11 1.297-2.992");
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

.kypsv4bum {
  stop-color: var(--svg-color--684235, #684235);
  stop-opacity: 0;
}

.l6ku6_bey {
  stop-color: var(--svg-color--27263f, #27263F);
}

.la5p1obbs {
  stop-color: var(--svg-color--462d2d, #462D2D);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln_tzqbjg {
  stop-color: var(--svg-color--846258, #846258);
  stop-opacity: 0;
}

.lnclpfbdm {
  stop-color: var(--svg-color--705653, #705653);
}

.lp4if9b4k {
  stop-color: var(--svg-color--180c11, #180C11);
}

.lyakdlbrr {
  stop-color: var(--svg-color--c0977d, #C0977D);
  stop-opacity: 0;
}

.m2odj8bqk {
  stop-color: var(--svg-color--725956, #725956);
  stop-opacity: 0;
}

.m7dikjbkp {
  stop-color: var(--svg-color--6b4e4c, #6B4E4C);
}

.mcb3mdbmq {
  fill: var(--svg-color--432f32, #432F32);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.mcpkokbsm {
  stop-color: var(--svg-color--6a4e4b, #6A4E4B);
  stop-opacity: 0;
}

.mdqyvu4ex {
  stop-color: var(--svg-color--187ed9, #187ED9);
  stop-opacity: 0;
}

.mm4k6y1ti {
  stop-color: var(--svg-color--54adff, #54ADFF);
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

.nagianp2z {
  stop-color: var(--svg-color--1a2115, #1A2115);
}

.nd_uzdbib {
  stop-color: var(--svg-color--7f4a45, #7F4A45);
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.nstnghbkd {
  stop-color: var(--svg-color--975a60, #975A60);
  stop-opacity: 0;
}

.o-suhjrka {
  stop-color: var(--svg-color--a17666, #A17666);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
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

.ok95vkw1c {
  stop-color: var(--svg-color--160e18, #160E18);
}

.omgobwb-x {
  stop-color: var(--svg-color--c39a7d, #C39A7D);
}

.omu6ddcev {
  stop-color: var(--svg-color--825e5a, #825E5A);
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

.pf0n6ab7v {
  stop-color: var(--svg-color--55302a, #55302A);
}

.phiaf5bvz {
  stop-color: var(--svg-color--784f55, #784F55);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqpxg6gcd {
  fill: var(--svg-color--ffa52a, #FFA52A);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.ps0fa7bxo {
  d: path("M23.088 18.457a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.px2yrv1tc {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M16 13.864c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.pyuxo8yyq {
  stop-color: var(--svg-color--281a18, #281A18);
  stop-opacity: 0;
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

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.qttrphznb {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.467a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.qylf6wbub {
  d: path("M8.85 6.407a.53.53 0 0 1 .529-.529h13.18a.53.53 0 0 1 0 1.059H9.378a.53.53 0 0 1-.53-.53");
}

.r2qtdocxn {
  stop-color: var(--svg-color--6d4837, #6D4837);
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.rlf5pscxx {
  stop-color: var(--svg-color--805957, #805957);
  stop-opacity: 0;
}

.ro5kwtkrd {
  stop-color: var(--svg-color--824d4f, #824D4F);
  stop-opacity: 0;
}

.ror6akb6y {
  stroke: var(--svg-color--443a3b, #443A3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.457 8.235c-.218-.171-.86-.524-1.691-.423");
}

.rs9lecbmb {
  stop-color: var(--svg-color--a57c6c, #A57C6C);
  stop-opacity: 0;
}

.rz3uprbtw {
  stop-color: var(--svg-color--725956, #725956);
}

.s1jm76o_g {
  stop-color: var(--svg-color--8b5548, #8B5548);
  stop-opacity: 0;
}

.sl-oxubgm {
  stop-color: var(--svg-color--7f5853, #7F5853);
}

.syu7jn24l {
  stop-color: var(--svg-color--b1736a, #B1736A);
  stop-opacity: 0;
}

.te0saggyn {
  stop-color: var(--svg-color--7d4d4c, #7D4D4C);
}

.tk0xf0bde {
  stop-color: var(--svg-color--49a1ec, #49A1EC);
}

.tp-3hccxn {
  stop-color: var(--svg-color--9777b8, #9777B8);
  stop-opacity: 0;
}

.u_90aebfc {
  stroke: var(--svg-color--110b17, #110B17);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.528 8.305c.217-.171.831-.519 1.662-.418");
}

.u_dvqebgf {
  stop-color: var(--svg-color--805957, #805957);
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

.uw0v2gb2x {
  stop-color: var(--svg-color--6a4944, #6A4944);
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.vn8pvc5iu {
  stop-color: var(--svg-color--519df1, #519DF1);
  stop-opacity: 0;
}

.vufvhcc4w {
  fill: var(--svg-color--af8973, #AF8973);
  d: path("M23.527 8.63c-1.524.44-2.582 1.437-2.928 1.89l-.21 2.95c.4.018.94.243 1.935-.466c1.164-1.042 1.72-2.577 1.999-3.546a.67.67 0 0 0-.136-.615a.64.64 0 0 0-.66-.213");
}

.w0eep96zc {
  stop-color: var(--svg-color--97674d, #97674D);
}

.w4q7dg2ti {
  stop-color: var(--svg-color--411d19, #411D19);
}

.wifu-cbwd {
  d: path("M8.912 18.457a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.wogh8-v4o {
  stop-color: var(--svg-color--3f70d2, #3F70D2);
}

.wsy42fbgm {
  stop-color: var(--svg-color--ae706a, #AE706A);
}

.x8yee1qkm {
  stop-color: var(--svg-color--956b65, #956B65);
  stop-opacity: 0;
}

.xakt0cbhn {
  stop-color: var(--svg-color--ad857a, #AD857A);
}

.xbdij97tt {
  d: path("m15.719 20.408l-2.871-4.067h6.265l-2.863 4.067c-.164.215-.395.2-.531 0");
}

.xego_hb4f {
  stop-color: var(--svg-color--815d56, #815D56);
  stop-opacity: 0;
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

.xu2rljbva {
  stop-color: var(--svg-color--55302a, #55302A);
  stop-opacity: 0;
}

.xvr3ve97x {
  stop-color: var(--svg-color--493130, #493130);
}

.y2vknabsu {
  d: path("M13.816 9.574a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.y59bi164p {
  d: path("m15.618 10.253l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.y5vxbvl2m {
  stop-color: var(--svg-color--c19e86, #C19E86);
  stop-opacity: 0;
}

.y6psmgb7b {
  stop-color: var(--svg-color--c0977d, #C0977D);
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

.yg8va_99z {
  stop-color: var(--svg-color--eddda3, #EDDDA3);
}

.ylyop8bmx {
  stop-color: var(--svg-color--7f5853, #7F5853);
  stop-opacity: 0;
}

.yngnm5bdn {
  stop-color: var(--svg-color--2d5fc4, #2D5FC4);
  stop-opacity: 0;
}

.yuhnzydjs {
  stop-color: var(--svg-color--8c695a, #8C695A);
}

.yvvekm_dy {
  stop-color: var(--svg-color--41393b, #41393B);
  stop-opacity: 0;
}

.yw13e1b2z {
  fill: var(--svg-color--825950, #825950);
  d: path("m15.447 10.449l-.57 1.838c-.098.378.136.756.467.756h.707c.331 0 .565-.384.468-.756l-.478-1.838c-.102-.408-.487-.408-.594 0");
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.z-thopeux {
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.z51dcdcri {
  stroke: var(--svg-color--302121, #302121);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.41 8.305c-.218-.171-.86-.523-1.69-.422");
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.z77zzmbkv {
  d: path("M5.071 26.776c0-6.036 4.893-10.928 10.929-10.928s10.929 4.892 10.929 10.928v3.318H5.07z");
}

.zhwrqyb9y {
  d: path("M20.612 12.016c.905-1.684 2.446-2.402 3.075-2.56c-.598 1.662-1.19 2.452-1.6 2.81c-.44.384-1.057.369-1.294.355z");
}

.zvqo526_s {
  stop-color: var(--svg-color--9a6e63, #9A6E63);
}

.zy43xh0vl {
  cx: 13.547px;
  cy: 9.956px;
  rx: 0.39px;
  ry: 0.197px;
}

.zyyeecb5g {
  stop-color: var(--svg-color--6d4f4b, #6D4F4B);
}

</style>
