<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFFcBnd)"><circle fill="url(#iUoIEbD)" class="cj0nb4gip"/></g><g filter="url(#iRfNaSb)"><circle fill="url(#iwILFcc)" class="uu85wsbky"/></g><g filter="url(#ivLLW4d)"><circle fill="url(#iQWf5fe)" class="lucf2ebsd"/><circle fill="url(#ieADqwe)" class="lucf2ebsd"/></g><g filter="url(#iXWuDCd)"><circle class="zdd3idbuq"/><circle fill="url(#iFLzfhz)" class="xv1wl_b5e"/><circle fill="url(#iyauole)" class="xv1wl_b5e"/></g><g filter="url(#iDImuxP)"><path class="suhuoefxm"/><path fill="url(#ifqlM3d)" class="ovmiylsie"/><path fill="url(#inm2jdh)" class="ovmiylsie"/><path fill="url(#iIsFIFe)" class="ovmiylsie"/><path fill="url(#i6FvFJc)" class="ovmiylsie"/><path fill="url(#izGcBhd)" class="ovmiylsie"/></g><path fill="url(#iQ32TAb)" class="ovmiylsie"/><path fill="url(#it9dNJb)" class="ovmiylsie"/><path fill="url(#idvh7nc)" class="ovmiylsie"/><path fill="url(#i1ryfob)" class="f0229regj"/><path fill="url(#io8R0nc)" class="f0229regj"/><path fill="url(#iupWyyd)" class="f0229regj"/><path fill="url(#irAwi8d)" class="f0229regj"/><path fill="url(#iW1Iv5t)" class="f0229regj"/><path fill="url(#inh7lSc)" class="f0229regj"/><path fill="url(#i8JJXrd)" class="f0229regj"/><path fill="url(#imuAEBe)" class="f0229regj"/><path fill="url(#iSqBlke)" class="f0229regj"/><g filter="url(#i61PwTc)"><path fill="url(#iqPrsTK)" class="x_mri4gas"/></g><rect fill="url(#ijGQGVb)" class="iuxb-78iw"/><path fill="url(#i2QzoZV)" class="veix-z38b"/><path fill="url(#i2vOWDd)" class="veix-z38b"/><path fill="url(#i4Z432d)" class="ygsync4_o"/><path fill="url(#ivztzoe)" class="ygsync4_o"/><path fill="url(#ihBX4Ob)" class="r_9_ioa3h"/><path fill="url(#iT9sB5K)" class="r_9_ioa3h"/><path fill="url(#ih88xxe)" class="eim_mrbrv"/><path fill="url(#iB5nmvP)" class="eim_mrbrv"/><path stroke="url(#ilZQpkc)" class="djebsbcjo"/><path stroke="url(#iSaruPc)" class="djebsbcjo"/><g filter="url(#iJ8ASec)"><path stroke="url(#iV2smEb)" class="psmqb459k"/></g><path stroke="url(#ibB8n0d)" class="w930jqbym"/><path stroke="url(#iyIeosc)" class="w930jqbym"/><path stroke="url(#iyzWL7d)" class="w930jqbym"/><path stroke="url(#iKgLD4b)" class="w930jqbym"/><path stroke="url(#i8h9Fdc)" class="cvtf9k6wz"/><path stroke="url(#iCGTUVd)" class="cvtf9k6wz"/><g filter="url(#i0LPb4c)"><path stroke="url(#igrivx)" class="bw3xffbxo"/></g><path stroke="url(#i9hBjid)" class="lc0lwfbjp"/><path stroke="url(#i0E7FYd)" class="lc0lwfbjp"/><path stroke="url(#ib5kWed)" class="lc0lwfbjp"/><path stroke="url(#icmYRqd)" class="lc0lwfbjp"/><path stroke="url(#i0vGyve)" class="zw6cmm23y"/><path stroke="url(#ia71ZOe)" class="zw6cmm23y"/><path stroke="url(#iEjqEie)" class="abd3-ibar"/><path stroke="url(#iVPjhAb)" class="abd3-ibar"/><path stroke="url(#idwOqgb)" class="abd3-ibar"/><path stroke="url(#iUYAgce)" class="abd3-ibar"/><path stroke="url(#iNGPBZZ)" class="hockzyb4d"/><path stroke="url(#iy6ah9d)" class="hockzyb4d"/><g filter="url(#i0wyjLd)"><path stroke="url(#iGQQ7je)" class="oz8qvprqg"/></g><g filter="url(#i8Q17se)"><path stroke="url(#iecRvXb)" class="drig65bxb"/></g><path stroke="url(#iOXD2Zc)" class="lgc2wbcpd"/><path stroke="url(#iMoeUSN)" class="lgc2wbcpd"/><path stroke="url(#i4xnjeS)" class="lgc2wbcpd"/><path stroke="url(#iMOE9cc)" class="lgc2wbcpd"/><path fill="url(#iPPFs6x)" class="eim_mrbrv"/><path fill="url(#iRYxGic)" class="r_9_ioa3h"/><path fill="url(#iAtPI7M)" class="r_9_ioa3h"/><g filter="url(#inh3Dnd)"><path fill="url(#iOz6e2d)" class="rl4irpj3j"/></g><g filter="url(#ipiHlse)"><path stroke="url(#ipBmWWm)" class="id0lipbed"/></g><g filter="url(#iXIMUZb)"><path fill="url(#iFfVDjr)" class="np58aonza"/><path fill="url(#ij9rOve)" class="np58aonza"/><path fill="url(#iqmLNJb)" class="np58aonza"/><path fill="url(#it8vPed)" class="np58aonza"/><path fill="url(#iy5Z9Ac)" class="np58aonza"/></g><g filter="url(#iSyz9Fd)"><path class="oxck_3b3i"/></g><g filter="url(#iPyJVib)"><path class="wdanbe2fv"/><path fill="url(#ivuvtZs)" class="zeplyxbfk"/><path fill="url(#izxGjlb)" class="zeplyxbfk"/><path fill="url(#i3vdOBd)" class="zeplyxbfk"/></g><path fill="url(#i7ssDdd)" class="zeplyxbfk"/><path stroke="url(#ign9Pwd)" class="qq92qrb7u"/><g filter="url(#iJxQqfc)"><path class="xp-njnlll"/></g><g filter="url(#i3nkpub)"><path class="jtbhxnbvx"/></g><path class="adfb76bkw"/><path fill="url(#iLtjeAB)" class="b72ef5bcl"/><path class="nb53z0s7p"/><g filter="url(#ip8vKcc)"><path class="s0s1z9ycm"/><path fill="url(#iNH3Nmc)" class="cr2pk2bha"/></g><g filter="url(#ifbD7uK)"><path fill="url(#iCJj4vd)" class="pcn7dpbez"/></g><path class="rtl5cbcmo"/><path fill="url(#iiu8Vud)" class="pbmolibqa"/><path class="v5ht5gbjt"/><g filter="url(#i1ryKgc)"><path fill="url(#iUMNxni)" class="pmx3__uvm"/></g><g filter="url(#iWSqODh)"><ellipse transform="rotate(-27.914 13.294 14.538)" class="ctub4ddyk"/><ellipse fill="url(#iInBVJv)" transform="rotate(-27.914 13.294 14.538)" class="ry8stmbsr"/></g><g filter="url(#igVrpDb)"><path stroke="url(#ilLesYb)" class="k44xquige"/></g><g filter="url(#imTPyfe)"><path stroke="url(#i2UWZ7T)" class="nzp6ncczm"/></g><defs><radialGradient id="iUoIEbD" cx="0" cy="0" r="1" gradientTransform="matrix(1.92698 0 0 3.37223 8.944 15.392)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="ieADqwe" cx="0" cy="0" r="1" gradientTransform="matrix(.90778 -.661 .75446 1.03612 21.632 15.102)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iFLzfhz" cx="0" cy="0" r="1" gradientTransform="matrix(.9018 -1.65868 .97083 .52783 21.178 16.294)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iyauole" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -8.103 33.501)scale(.40062 .51644)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="ifqlM3d" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.327 8.37)scale(6.15602 10.4689)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iIsFIFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.07338 -2.04404 1.00387 -.03604 11.387 11.598)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i6FvFJc" cx="0" cy="0" r="1" gradientTransform="matrix(.9434 -2.15935 1.76112 .76942 20.632 13.485)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="izGcBhd" cx="0" cy="0" r="1" gradientTransform="matrix(1.09015 1.35268 -1.19432 .96253 15.14 5.948)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iQ32TAb" cx="0" cy="0" r="1" gradientTransform="matrix(7.90625 -5.75 9.00838 12.38652 14.844 15.26)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="jonj30b4s"/><stop offset=".968" class="x4-gq5boe"/></radialGradient><radialGradient id="it9dNJb" cx="0" cy="0" r="1" gradientTransform="matrix(.75 2.75 -4.97398 1.35654 17.906 5.385)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="etgd_-bkk"/><stop offset="1" class="p6x41sblh"/></radialGradient><radialGradient id="idvh7nc" cx="0" cy="0" r="1" gradientTransform="matrix(1.2813 1.5393 -3.449 2.8709 11.219 7.845)" gradientUnits="userSpaceOnUse"><stop class="kvgw8i3ed"/><stop offset="1" class="ru1-8biig"/></radialGradient><radialGradient id="io8R0nc" cx="0" cy="0" r="1" gradientTransform="matrix(8.8125 0 0 9.43494 11 29.99)" gradientUnits="userSpaceOnUse"><stop class="q920b5bgt"/><stop offset="1" class="hmv6xsb8e"/></radialGradient><radialGradient id="iupWyyd" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -8.62501 6.82131 4.1521 23.375 24.35)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="bawjzlb6r"/><stop offset="1" class="ati7d-krq"/></radialGradient><radialGradient id="irAwi8d" cx="0" cy="0" r="1" gradientTransform="matrix(3 0 0 4.4849 7.5 29.99)" gradientUnits="userSpaceOnUse"><stop class="qe_-3ab1e"/><stop offset="1" class="chsdmobsg"/></radialGradient><radialGradient id="iW1Iv5t" cx="0" cy="0" r="1" gradientTransform="matrix(.87505 5.5 -7.00176 1.11398 15.126 19.538)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gwwxrtb_v"/><stop offset="1" class="ssq48xbfd"/></radialGradient><radialGradient id="inh7lSc" cx="0" cy="0" r="1" gradientTransform="rotate(118.413 2.335 6.065)scale(1.08366 3.24985)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zpk636z_v"/><stop offset="1" class="mtfxop-pk"/></radialGradient><radialGradient id="i8JJXrd" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 0 0 28.1734 1.625 13.788)" gradientUnits="userSpaceOnUse"><stop class="sg9fyvxai"/><stop offset="1" class="r0adxvbzx"/></radialGradient><radialGradient id="imuAEBe" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.68753 -3.8615 2.52917 25.625 5.913)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="t4nmlm7ht"/><stop offset="1" class="q4q53m76f"/></radialGradient><radialGradient id="iSqBlke" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .84375 -2.45037 1.58819 23.657 6.476)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="ubeq2y34d"/><stop offset="1" class="r7flkhbpm"/></radialGradient><radialGradient id="iqPrsTK" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xli568bjl"/><stop offset="1" class="dvyuy-plf"/></radialGradient><radialGradient id="ijGQGVb" cx="0" cy="0" r="1" gradientTransform="rotate(-112.749 16.634 6.815)scale(3.15174 2.83444)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="mqra8-37f"/><stop offset="1" class="q3706en1b"/></radialGradient><radialGradient id="i2QzoZV" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dp3nzmbzl"/><stop offset="1" class="wkrt2mblo"/></radialGradient><radialGradient id="i2vOWDd" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="i0f64nbug"/><stop offset="1" class="ucmtgi-2a"/></radialGradient><radialGradient id="i4Z432d" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.276 6.464)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="xr5reebcs"/><stop offset="1" class="z9wcvylbn"/></radialGradient><radialGradient id="ivztzoe" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.401 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zi5l5kj0o"/><stop offset="1" class="mcuv6-nuk"/></radialGradient><radialGradient id="ihBX4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="cxb3glbzc"/><stop offset="1" class="t9spukb2f"/></radialGradient><radialGradient id="iT9sB5K" cx="0" cy="0" r="1" gradientTransform="matrix(.74502 .76747 -3.62255 3.5166 8.584 3.413)" gradientUnits="userSpaceOnUse"><stop class="hdbftdbag"/><stop offset="1" class="gnvn91bpk"/></radialGradient><radialGradient id="ih88xxe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.46 5.257)" gradientUnits="userSpaceOnUse"><stop class="rks0_83_d"/><stop offset="1" class="vua1r5-2d"/></radialGradient><radialGradient id="iB5nmvP" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="c8sl-2enp"/><stop offset="1" class="lxeh84buj"/></radialGradient><radialGradient id="iSaruPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.16682 -1.23816 5.34461 -.72007 12.855 3.344)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="iyzWL7d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.64176 1.91051 -3.15495 -6.01388 20.913 1.013)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="iKgLD4b" cx="0" cy="0" r="1" gradientTransform="rotate(-80.652 11.63 -9.837)scale(1.19569 6.01339)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iCGTUVd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.22 8.882 -4.991)scale(1.02308 4.45604)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="ib5kWed" cx="0" cy="0" r="1" gradientTransform="rotate(136.804 9.736 4.212)scale(4.70997 8.35502)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="icmYRqd" cx="0" cy="0" r="1" gradientTransform="matrix(.10745 -1.4828 5.40082 .39136 18.499 3.933)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="ia71ZOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0107 -1.01703 4.29921 -.04521 13.901 4.511)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="idwOqgb" cx="0" cy="0" r="1" gradientTransform="rotate(150.94 9.209 4.016)scale(2.77209 4.18391)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="iUYAgce" cx="0" cy="0" r="1" gradientTransform="matrix(.09106 -1.00369 6.14439 .55743 18.35 4.439)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iy6ah9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.01775 -1.34298 3.63064 -.04798 13.474 5.765)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="i4xnjeS" cx="0" cy="0" r="1" gradientTransform="rotate(127.201 9.028 6.4)scale(3.51838 3.62395)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="x6vydhb_v"/><stop offset=".991" class="e0z1nhb7e"/></radialGradient><radialGradient id="iMOE9cc" cx="0" cy="0" r="1" gradientTransform="matrix(.07604 -1.3001 4.12187 .24108 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iPPFs6x" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07831 4.16712 -14.86837 -3.84744 20.85 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="lv-cucc-s"/><stop offset=".935" class="o2ym0bbuj"/></radialGradient><radialGradient id="iRYxGic" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="y8zuwqb-d"/><stop offset="1" class="de46s3h_f"/></radialGradient><radialGradient id="iAtPI7M" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="a1et2ybqq"/><stop offset="1" class="jts0ojbqo"/></radialGradient><radialGradient id="iOz6e2d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53124 -8.125 5.12798 -2.85982 9.094 24.881)" gradientUnits="userSpaceOnUse"><stop class="x034jqb5d"/><stop offset="1" class="rpjijqwhi"/></radialGradient><radialGradient id="ij9rOve" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.95923 -8.21233 0 16.869 13.77)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="qj-kubcuz"/><stop offset="1" class="w32qynbtg"/></radialGradient><radialGradient id="it8vPed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.43528 1.76649 0 18.567 13.996)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iy5Z9Ac" cx="0" cy="0" r="1" gradientTransform="scale(1.89931 1.52728)rotate(-90 8.14 1)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iLtjeAB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .99173 -1.17348 0 18.383 15.01)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iNH3Nmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2546 -.3281 .4517 -.35053 18.132 14.736)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiu8Vud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .99179 -1.17354 0 13.592 15.01)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iInBVJv" cx="0" cy="0" r="1" gradientTransform="matrix(-.0085 -.54242 .652 -.0102 13.278 14.884)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iwILFcc" x1="10.777" x2="10.073" y1="15.698" y2="15.698" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iQWf5fe" x1="22.416" x2="21.517" y1="14.194" y2="16.979" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="inm2jdh" x1="10.653" x2="13.839" y1="15.099" y2="9.439" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="i1ryfob" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="b9v5e-b3e"/><stop offset="1" class="t_qwphcjx"/></linearGradient><linearGradient id="ilZQpkc" x1="14.261" x2="10.736" y1="2.588" y2="4.348" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="iV2smEb" x1="14.299" x2="11.472" y1="2.495" y2="4.331" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="ibB8n0d" x1="19.282" x2="20.479" y1="2.332" y2="3.309" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iyIeosc" x1="16.583" x2="21.672" y1="3.146" y2="3.689" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="i8h9Fdc" x1="15.286" x2="12.235" y1="3.297" y2="4.422" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="igrivx" x1="15.432" x2="12.281" y1="3.185" y2="4.567" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="i9hBjid" x1="19.724" x2="20.597" y1="3.443" y2="3.587" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="i0E7FYd" x1="15.618" x2="20.781" y1="4.258" y2="4.234" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="i0vGyve" x1="14.956" x2="12.465" y1="4.165" y2="5.276" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="iEjqEie" x1="19.214" x2="19.802" y1="4.234" y2="4.398" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iVPjhAb" x1="16.317" x2="19.96" y1="4.575" y2="4.546" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="iNGPBZZ" x1="14.472" x2="11.788" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="iGQQ7je" x1="14.505" x2="12.194" y1="5.201" y2="5.924" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="iecRvXb" x1="15.088" x2="11.938" y1="4.045" y2="5.427" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="iOXD2Zc" x1="19.589" x2="20.216" y1="5.254" y2="5.381" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iMoeUSN" x1="16.849" x2="20.295" y1="5.882" y2="5.868" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="ipBmWWm" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="tuzqszfby"/><stop offset="1" class="ljv2-xbix"/></linearGradient><linearGradient id="iFfVDjr" x1="20.422" x2="12.036" y1="15.82" y2="17.07" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iqmLNJb" x1="10.065" x2="12.605" y1="18.78" y2="18.449" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="ivuvtZs" x1="15.041" x2="16.072" y1="16.544" y2="16.544" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="izxGjlb" x1="17.021" x2="15.895" y1="16.898" y2="16.882" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="i3vdOBd" x1="16.204" x2="16.204" y1="17.713" y2="17.084" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="i7ssDdd" x1="16.128" x2="16.128" y1="17.759" y2="17.575" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="ign9Pwd" x1="14.852" x2="15.329" y1="19.487" y2="18.732" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iCJj4vd" x1="19.237" x2="18.893" y1="14.703" y2="14.915" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUMNxni" x1="14.409" x2="14.064" y1="14.703" y2="14.915" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilLesYb" x1="19.254" x2="18.793" y1="12.353" y2="11.41" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i2UWZ7T" x1="13.429" x2="12.123" y1="12.213" y2="11.665" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="iFFcBnd" width="3.866" height="3.666" x="8.944" y="13.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3727"/></filter><filter id="iRfNaSb" width="3.185" height="3.185" x="9.184" y="13.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".25"/></filter><filter id="ivLLW4d" width="3.916" height="3.916" x="19.39" y="13.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3727"/></filter><filter id="iXWuDCd" width="3.185" height="3.185" x="19.631" y="13.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".25"/></filter><filter id="iDImuxP" width="13.838" height="9.332" x="9.072" y="5.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3727"/></filter><filter id="i61PwTc" width="15.688" height="8.156" x="9.357" y="22.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".375"/></filter><filter id="iJ8ASec" width="3.938" height="1.28" x="10.688" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".125"/></filter><filter id="i0LPb4c" width="3.966" height="1.018" x="11.791" y="2.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".125"/></filter><filter id="i0wyjLd" width="2.922" height="1.004" x="11.925" y="4.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".125"/></filter><filter id="i8Q17se" width="3.966" height="1.018" x="11.448" y="3.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".125"/></filter><filter id="inh3Dnd" width="9.632" height="11.909" x="1.844" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".25"/></filter><filter id="ipiHlse" width="4.094" height="4.656" x="7.923" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".25"/></filter><filter id="iXIMUZb" width="11.391" height="13.458" x="10.326" y="9.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3727"/></filter><filter id="iSyz9Fd" width="3.433" height="4.444" x="14.012" y="14.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".375"/></filter><filter id="iPyJVib" width="2.561" height="3.444" x="14.71" y="14.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".125"/></filter><filter id="iJxQqfc" width="3.247" height="2.017" x="17.289" y="11.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3727"/></filter><filter id="i3nkpub" width="3.248" height="2.017" x="11.636" y="11.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3727"/></filter><filter id="ip8vKcc" width=".844" height=".745" x="17.587" y="14.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".05"/></filter><filter id="ifbD7uK" width=".939" height=".964" x="18.519" y="14.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".1"/></filter><filter id="i1ryKgc" width="1.044" height="1.103" x="13.641" y="14.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".1"/></filter><filter id="iWSqODh" width=".983" height=".754" x="12.803" y="14.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".05"/></filter><filter id="igVrpDb" width="3.531" height="1.973" x="17.064" y="11.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".25"/></filter><filter id="imTPyfe" width="3.616" height="2.036" x="11.332" y="11.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3727" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-ok-medium-light" /></template>
<style>
.a1et2ybqq {
  stop-color: var(--svg-color--edb090, #EDB090);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.adfb76bkw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.612 13.822c.717 0 1.323.494 1.488 1.162a.3.3 0 0 1-.294.374h-2.45a.253.253 0 0 1-.249-.299a1.535 1.535 0 0 1 1.505-1.237");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ati7d-krq {
  stop-color: var(--svg-color--298dff, #298DFF);
  stop-opacity: 0;
}

.b72ef5bcl {
  d: path("M18.385 14.12a.98.98 0 0 1 .944 1.238h-1.892a.984.984 0 0 1 .948-1.238");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.b9v5e-b3e {
  stop-color: var(--svg-color--3ca8ff, #3CA8FF);
}

.bawjzlb6r {
  stop-color: var(--svg-color--298dff, #298DFF);
}

.bswoa5a7i {
  stop-color: var(--svg-color--d6a184, #D6A184);
  stop-opacity: 0;
}

.bw3xffbxo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.167 3.374c.43-.109 2.2-.358 3.216-.233");
}

.c8sl-2enp {
  stop-color: var(--svg-color--cca180, #CCA180);
}

.chsdmobsg {
  stop-color: var(--svg-color--499efa, #499EFA);
  stop-opacity: 0;
}

.cj0nb4gip {
  cx: 10.777px;
  cy: 15.392px;
  r: 1.833px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr2pk2bha {
  d: path("M18.313 14.327c.07.093-.076.207-.242.331s-.289.212-.359.118c-.07-.093.008-.27.174-.393c.166-.125.357-.15.427-.056");
}

.ctub4ddyk {
  cx: 13.294px;
  cy: 14.538px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.428px;
  ry: 0.216px;
}

.cvtf9k6wz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.cxb3glbzc {
  stop-color: var(--svg-color--eab594, #EAB594);
}

.cxjjb1-je {
  stop-color: var(--svg-color--d6a184, #D6A184);
}

.de46s3h_f {
  stop-color: var(--svg-color--d48e7a, #D48E7A);
  stop-opacity: 0;
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dp3nzmbzl {
  stop-color: var(--svg-color--2d99fd, #2D99FD);
}

.dqms9qb3g {
  stop-color: var(--svg-color--c98b5e, #C98B5E);
}

.drig65bxb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.823 4.234c.43-.11 2.2-.359 3.216-.234");
}

.dvyuy-plf {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
  stop-opacity: 0;
}

.e0z1nhb7e {
  stop-color: var(--svg-color--cc9167, #CC9167);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.etgd_-bkk {
  stop-color: var(--svg-color--c8a86f, #C8A86F);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f0229regj {
  d: path("M7.312 5.365c-.203-.057-.676-.154-.945-.086c-.336.086-.594.329-.812.688c-.175.287-1.47 2.48-2.094 3.539c-.563.823-1.625 3.088-1.375 5.563c.1 1.662.781 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.376-5.563a915 915 0 0 0-2.094-3.54c-.218-.358-.476-.6-.812-.687c-.269-.068-.742.03-.945.086L21.5 7.53c-.352.415-.19.967-.055 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a50 50 0 0 0-1.343-.59c-.295.137-.22.125-.551.175v.29a2.307 2.307 0 1 1-4.615 0v-.384c-.298-.05-.329.076-.593-.043c-.418.155-1.092.472-1.252.552a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.135-.213.297-.765-.055-1.18z");
}

.ft5dv1b6b {
  fill: none;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gnvn91bpk {
  stop-color: var(--svg-color--c69a7a, #C69A7A);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gwwxrtb_v {
  stop-color: var(--svg-color--1d5894, #1D5894);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hdbftdbag {
  stop-color: var(--svg-color--c69a7a, #C69A7A);
}

.hmv6xsb8e {
  stop-color: var(--svg-color--2691ff, #2691FF);
  stop-opacity: 0;
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i5892ackl {
  stop-color: var(--svg-color--d39869, #D39869);
  stop-opacity: 0;
}

.id0lipbed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jonj30b4s {
  stop-color: var(--svg-color--fadfa7, #FADFA7);
  stop-opacity: 0;
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtbhxnbvx {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m11.847 12.406l.001-.002l.002-.001l.005-.004l.013-.01a2 2 0 0 1 .17-.119a3 3 0 0 1 .461-.231a3.1 3.1 0 0 1 1.64-.174a.586.586 0 0 1-.183 1.158a1.94 1.94 0 0 0-1.026.106a1.7 1.7 0 0 0-.338.181a.586.586 0 0 1-.745-.904");
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jts0ojbqo {
  stop-color: var(--svg-color--edb090, #EDB090);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k44xquige {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.814 12.247c.472-.083 1.393-.06 2.03.437");
}

.kvgw8i3ed {
  stop-color: var(--svg-color--c3ab80, #C3AB80);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lc0lwfbjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lgc2wbcpd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljv2-xbix {
  stop-color: var(--svg-color--3b95f9, #3B95F9);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lucf2ebsd {
  cx: 21.223px;
  cy: 15.392px;
  r: 1.833px;
}

.lv-cucc-s {
  stop-color: var(--svg-color--ce886b, #CE886B);
  stop-opacity: 0;
}

.lxeh84buj {
  stop-color: var(--svg-color--cca180, #CCA180);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcuv6-nuk {
  stop-color: var(--svg-color--4298d4, #4298D4);
  stop-opacity: 0;
}

.mqra8-37f {
  stop-color: var(--svg-color--e1af99, #E1AF99);
}

.mtfxop-pk {
  stop-color: var(--svg-color--43bbff, #43BBFF);
  stop-opacity: 0;
}

.nb53z0s7p {
  fill: var(--svg-color--000, #000);
  d: path("M17.824 15.1c0-.312.25-.561.561-.561a.56.56 0 0 1 .499.819h-.993a.5.5 0 0 1-.067-.258");
}

.np58aonza {
  d: path("m10.39 14.72l.054.001s-.059-.937-.118-1.58c0-.294.118-.645.354-.82l.177-.176c.294-.235.412-.586.412-.937v-.937a.57.57 0 0 1 .471-.586c.707-.176 2.18-.469 4.3-.469s3.593.293 4.3.469c.235.058.47.293.47.585v.938c0 .35.177.702.413.937c.551.386.517.598.471 1.054a51 51 0 0 0-.118 1.581h.02l-.292 4.346c-.176 1.944-1.703 3.298-3.525 3.298h-3.525c-1.88 0-3.35-1.354-3.525-3.298z");
}

.nt7gwkb2p {
  stop-color: var(--svg-color--d39869, #D39869);
}

.nzp6ncczm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.082 12.816c.36-.317 1.144-.652 2.117-.497");
}

.o2ym0bbuj {
  stop-color: var(--svg-color--ce886b, #CE886B);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.ovmiylsie {
  d: path("m21.282 8.28l.471.234c.825.41 1.296 1.347 1.12 2.342l-.649 3.338c-.057.345-.285.577-.628.586h-.02s.06-.996.118-1.581c.048-.476-.035-.621-.471-1.054c-.236-.235-.412-.586-.412-.937v-.938c0-.292-.236-.527-.471-.585c-.707-.176-2.18-.469-4.3-.469s-3.593.293-4.3.469a.57.57 0 0 0-.471.585v.938c0 .35-.118.702-.412.937l-.177.175c-.236.176-.354.527-.354.82c.06.644.118 1.581.118 1.581l-.054-.002a.695.695 0 0 1-.653-.583l-.647-3.338c-.118-.937.353-1.875 1.178-2.284l.47-.235c.295-.175.59-.41.884-.644l1.06-1.113c.648-.585 1.59-.761 2.415-.351a3.23 3.23 0 0 0 1.826 0c.884-.293 1.885-.059 2.592.586l.883.878c.236.293.53.469.884.644");
}

.oxck_3b3i {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.688 15.258l-.9 1.867c-.112.383.156.767.535.767h.81c.38 0 .647-.39.536-.767l-.547-1.867c-.118-.413-.311-.413-.434 0");
}

.oz8qvprqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.p6x41sblh {
  stop-color: var(--svg-color--f4d79b, #F4D79B);
  stop-opacity: 0;
}

.pbmolibqa {
  d: path("M13.59 14.12a.98.98 0 0 0-.944 1.238h1.893q.034-.127.035-.258a.987.987 0 0 0-.984-.98");
}

.pcn7dpbez {
  d: path("M19.258 14.97a.92.92 0 0 0-.254-.507l-.285.313l.128.25z");
}

.ph5523b-j {
  stop-color: var(--svg-color--e9b895, #E9B895);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmx3__uvm {
  d: path("M14.485 14.984c0-.316-.258-.527-.327-.591l-.317.306l.195.397z");
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.psmqb459k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.064 3.03c.68-.344 2.468-.57 3.187-.524");
}

.ptbyyggko {
  stop-color: var(--svg-color--d09472, #D09472);
}

.ptik26i9i {
  stop-color: var(--svg-color--c19471, #C19471);
  stop-opacity: 0;
}

.q3706en1b {
  stop-color: var(--svg-color--b37973, #B37973);
}

.q4q53m76f {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
  stop-opacity: 0;
}

.q920b5bgt {
  stop-color: var(--svg-color--2691ff, #2691FF);
}

.qe_-3ab1e {
  stop-color: var(--svg-color--499efa, #499EFA);
}

.qj-kubcuz {
  stop-color: var(--svg-color--c88c89, #C88C89);
  stop-opacity: 0;
}

.qp3l4dbyt {
  stop-color: var(--svg-color--c19471, #C19471);
}

.qq92qrb7u {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.493 18.424a.22.22 0 0 0-.26.045a.2.2 0 0 0-.022.257c.376.57 1.032.95 1.78.95c.746 0 1.403-.38 1.78-.95a.2.2 0 0 0-.023-.26a.22.22 0 0 0-.26-.042a3.2 3.2 0 0 1-1.498.355a3.25 3.25 0 0 1-1.498-.355Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r0adxvbzx {
  stop-color: var(--svg-color--54acf3, #54ACF3);
  stop-opacity: 0;
}

.r7flkhbpm {
  stop-color: var(--svg-color--419ae2, #419AE2);
  stop-opacity: 0;
}

.rks0_83_d {
  stop-color: var(--svg-color--f5c39b, #F5C39B);
}

.rl4irpj3j {
  d: path("M7.788 26.79L2.344 16.695l4.594-.812l4.038 7.877c-1.35 2.025-2.688 2.865-3.188 3.032");
}

.rpjijqwhi {
  stop-color: var(--svg-color--2882ff, #2882FF);
  stop-opacity: 0;
}

.rtl5cbcmo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.363 13.821c-.717 0-1.323.495-1.488 1.163a.3.3 0 0 0 .294.374h2.45c.155 0 .28-.143.25-.299a1.54 1.54 0 0 0-1.506-1.238");
}

.ru1-8biig {
  stop-color: var(--svg-color--dcc097, #DCC097);
  stop-opacity: 0;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.ry8stmbsr {
  cx: 13.294px;
  cy: 14.538px;
  rx: 0.428px;
  ry: 0.216px;
}

.s0s1z9ycm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.313 14.327c.07.093-.076.207-.242.331s-.289.212-.359.118c-.07-.093.008-.27.174-.393c.166-.125.357-.15.427-.056");
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s45c4_k9i {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sg9fyvxai {
  stop-color: var(--svg-color--54acf3, #54ACF3);
}

.shmkvjbbg {
  stop-color: var(--svg-color--e9b895, #E9B895);
  stop-opacity: 0;
}

.ssq48xbfd {
  stop-color: var(--svg-color--1d5894, #1D5894);
  stop-opacity: 0;
}

.suhuoefxm {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m21.282 8.28l.471.234c.825.41 1.296 1.347 1.12 2.342l-.649 3.338c-.057.345-.285.577-.628.586h-.02s.06-.996.118-1.581c.048-.476-.035-.621-.471-1.054c-.236-.235-.412-.586-.412-.937v-.938c0-.292-.236-.527-.471-.585c-.707-.176-2.18-.469-4.3-.469s-3.593.293-4.3.469a.57.57 0 0 0-.471.585v.938c0 .35-.118.702-.412.937l-.177.175c-.236.176-.354.527-.354.82c.06.644.118 1.581.118 1.581l-.054-.002a.695.695 0 0 1-.653-.583l-.647-3.338c-.118-.937.353-1.875 1.178-2.284l.47-.235c.295-.175.59-.41.884-.644l1.06-1.113c.648-.585 1.59-.761 2.415-.351a3.23 3.23 0 0 0 1.826 0c.884-.293 1.885-.059 2.592.586l.883.878c.236.293.53.469.884.644");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t_qwphcjx {
  stop-color: var(--svg-color--2a99ff, #2A99FF);
}

.t4nmlm7ht {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
}

.t9spukb2f {
  stop-color: var(--svg-color--ddaf8a, #DDAF8A);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tuzqszfby {
  stop-color: var(--svg-color--3a95fa, #3A95FA);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ubeq2y34d {
  stop-color: var(--svg-color--419ae2, #419AE2);
}

.ucmtgi-2a {
  stop-color: var(--svg-color--49abff, #49ABFF);
  stop-opacity: 0;
}

.uu85wsbky {
  cx: 10.777px;
  cy: 15.392px;
  r: 1.093px;
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v5ht5gbjt {
  fill: var(--svg-color--000, #000);
  d: path("M14.151 15.1a.56.56 0 0 0-.561-.562a.56.56 0 0 0-.499.82h.993a.56.56 0 0 0 .067-.258");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.veix-z38b {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.155 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vua1r5-2d {
  stop-color: var(--svg-color--d5a482, #D5A482);
}

.w20q0hgpg {
  stop-color: var(--svg-color--d09472, #D09472);
  stop-opacity: 0;
}

.w32qynbtg {
  stop-color: var(--svg-color--a57182, #A57182);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wdanbe2fv {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.57 15.08l-.583 1.865a.592.592 0 0 0 .572.768h.863c.405 0 .69-.39.572-.768l-.584-1.866c-.125-.413-.708-.413-.84 0");
}

.wkrt2mblo {
  stop-color: var(--svg-color--1284d5, #1284D5);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x034jqb5d {
  stop-color: var(--svg-color--2882ff, #2882FF);
}

.x4-gq5boe {
  stop-color: var(--svg-color--9d8c79, #9D8C79);
}

.x6vydhb_v {
  stop-color: var(--svg-color--cc9167, #CC9167);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xli568bjl {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xp-njnlll {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m20.075 12.406l-.002-.002l-.002-.001l-.005-.004l-.013-.01a2 2 0 0 0-.17-.119a3 3 0 0 0-.46-.231a3.1 3.1 0 0 0-1.64-.174a.586.586 0 0 0 .183 1.158a1.94 1.94 0 0 1 1.025.106a1.7 1.7 0 0 1 .339.181a.586.586 0 0 0 .745-.904");
}

.xr5reebcs {
  stop-color: var(--svg-color--4bb4ff, #4BB4FF);
}

.xra9oc37j {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xv1wl_b5e {
  cx: 21.223px;
  cy: 15.392px;
  r: 1.093px;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.y8zuwqb-d {
  stop-color: var(--svg-color--d48e7a, #D48E7A);
}

.ygsync4_o {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.155-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.z9wcvylbn {
  stop-color: var(--svg-color--347bc6, #347BC6);
}

.zdd3idbuq {
  cx: 21.223px;
  cy: 15.392px;
  r: 1.093px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zeplyxbfk {
  d: path("m15.57 15.08l-.583 1.865a.592.592 0 0 0 .572.768h.863c.405 0 .69-.39.572-.768l-.584-1.866c-.125-.413-.708-.413-.84 0");
}

.zi5l5kj0o {
  stop-color: var(--svg-color--4298d4, #4298D4);
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zpk636z_v {
  stop-color: var(--svg-color--43bbff, #43BBFF);
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

</style>
