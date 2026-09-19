<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9PlWXc)"><circle fill="url(#iG4aAJe)" class="cj0nb4gip"/></g><g filter="url(#i4sUQLT)"><circle fill="url(#ijFPqje)" class="uu85wsbky"/></g><g filter="url(#iHxIJ4q)"><circle fill="url(#iaQAaRs)" class="lucf2ebsd"/><circle fill="url(#ieWtTNd)" class="lucf2ebsd"/></g><g filter="url(#iYeiHFe)"><circle class="ci8i_zxyy"/><circle fill="url(#iykixvb)" class="xv1wl_b5e"/><circle fill="url(#icBB7xb)" class="xv1wl_b5e"/></g><g filter="url(#itLlu4d)"><path class="pf8qhd_wg"/><path fill="url(#iCHp4vb)" class="h12lzabje"/><path fill="url(#ieHp7me)" class="h12lzabje"/><path fill="url(#iWvW2Zd)" class="h12lzabje"/><path fill="url(#ivopd5m)" class="h12lzabje"/></g><g filter="url(#iK268ke)"><path stroke="url(#ireSPNe)" class="tmlw0f1oe"/></g><path fill="url(#i1ryfob)" class="f0229regj"/><path fill="url(#io8R0nc)" class="f0229regj"/><path fill="url(#iupWyyd)" class="f0229regj"/><path fill="url(#irAwi8d)" class="f0229regj"/><path fill="url(#iW1Iv5t)" class="f0229regj"/><path fill="url(#inh7lSc)" class="f0229regj"/><path fill="url(#i8JJXrd)" class="f0229regj"/><path fill="url(#imuAEBe)" class="f0229regj"/><path fill="url(#iSqBlke)" class="f0229regj"/><g filter="url(#i5scKHb)"><path fill="url(#iqPrsTK)" class="x_mri4gas"/></g><rect fill="url(#ivdZkMc)" class="iuxb-78iw"/><path fill="url(#i2QzoZV)" class="ggskh2bzm"/><path fill="url(#i2vOWDd)" class="ggskh2bzm"/><path fill="url(#i4Z432d)" class="dw85flb0t"/><path fill="url(#i3nxMBb)" class="dw85flb0t"/><path fill="url(#i9ATG8d)" class="r_9_ioa3h"/><path fill="url(#ijFyBlc)" class="r_9_ioa3h"/><path fill="url(#izG65ob)" class="eim_mrbrv"/><path fill="url(#iqfRMNF)" class="eim_mrbrv"/><path stroke="url(#i7AyVUc)" class="djebsbcjo"/><path stroke="url(#i3fcDvw)" class="djebsbcjo"/><path stroke="url(#iMCL7Ep)" class="djebsbcjo"/><g filter="url(#ijFewce)"><path stroke="url(#iF42OSy)" class="psmqb459k"/></g><path class="zoy4bqbmr"/><path stroke="url(#ifXGk1d)" class="w930jqbym"/><path stroke="url(#iGBGCYb)" class="w930jqbym"/><path stroke="url(#ipfeOLc)" class="cvtf9k6wz"/><path stroke="url(#i1auEWd)" class="cvtf9k6wz"/><path stroke="url(#iJgax7d)" class="cvtf9k6wz"/><g filter="url(#iJvoazb)"><path stroke="url(#iVmAHha)" class="bw3xffbxo"/></g><path class="o4lj9bc9c"/><path stroke="url(#iG8mdDe)" class="lc0lwfbjp"/><path stroke="url(#ilvOO4b)" class="lc0lwfbjp"/><path stroke="url(#iaB4TJb)" class="zw6cmm23y"/><path stroke="url(#ifw7fHd)" class="zw6cmm23y"/><path stroke="url(#iqbvtPe)" class="zw6cmm23y"/><path class="jh3kajxvi"/><path stroke="url(#i5FFNib)" class="abd3-ibar"/><path stroke="url(#iIu8Rhd)" class="abd3-ibar"/><path stroke="url(#iRHom1b)" class="hockzyb4d"/><path stroke="url(#i8nLFcd)" class="hockzyb4d"/><path stroke="url(#iU90igb)" class="hockzyb4d"/><g filter="url(#igGhk6c)"><path stroke="url(#iLMBJiH)" class="oz8qvprqg"/></g><g filter="url(#iNNKDee)"><path stroke="url(#iBjn1Hd)" class="drig65bxb"/></g><path class="pwg4g4b6s"/><path stroke="url(#iDQOVwm)" class="lgc2wbcpd"/><path stroke="url(#iIpvJFe)" class="lgc2wbcpd"/><path fill="url(#iLjyNhd)" class="eim_mrbrv"/><path fill="url(#ixYC5Kd)" class="r_9_ioa3h"/><path fill="url(#iSyDdEe)" class="r_9_ioa3h"/><g filter="url(#iCJDDXc)"><path fill="url(#iOz6e2d)" class="rl4irpj3j"/></g><g filter="url(#iKnM6Ke)"><path stroke="url(#ipBmWWm)" class="id0lipbed"/></g><g filter="url(#iL68X6b)"><path fill="url(#iE8u6Dc)" class="kac_i9wmf"/><path fill="url(#iuC8oHd)" class="kac_i9wmf"/><path fill="url(#iTWzvPe)" class="kac_i9wmf"/><path fill="url(#ieG8M5c)" class="kac_i9wmf"/><path fill="url(#i7uQyub)" class="kac_i9wmf"/><path fill="url(#ijXwnhc)" class="kac_i9wmf"/></g><g filter="url(#ixbYKgJ)"><path fill="url(#ixKh99c)" class="kj76vd-0e"/></g><g filter="url(#i7rWrtc)"><path class="rg-7ehwto"/></g><g filter="url(#iytyvld)"><path class="mjj8sabfd"/><path fill="url(#iPEayOb)" class="zeplyxbfk"/><path fill="url(#iZztVzd)" class="zeplyxbfk"/><path fill="url(#ixrDqTc)" class="zeplyxbfk"/><path fill="url(#iKYWf9d)" class="zeplyxbfk"/></g><path fill="url(#ifwtd1b)" class="zeplyxbfk"/><path stroke="url(#i5dsXuB)" class="qq92qrb7u"/><g filter="url(#ilyRQlc)"><path class="g7mweqbwu"/></g><g filter="url(#imzBS7c)"><path class="q2kzydr5a"/></g><path class="f_t_65bdv"/><path fill="url(#irlXONc)" class="tdjdjpb5y"/><path class="nb53z0s7p"/><g filter="url(#iCCpuUw)"><path class="u_sj9acab"/><path fill="url(#iNH3Nmc)" class="ouf_rrb9s"/></g><g filter="url(#iMWurPb)"><path fill="url(#iCJj4vd)" class="pcn7dpbez"/></g><path class="rtl5cbcmo"/><path fill="url(#i0rZPze)" class="u5as6fnzn"/><path class="v5ht5gbjt"/><g filter="url(#i7wfiTy)"><path fill="url(#iUMNxni)" class="y0hurf_aa"/></g><g filter="url(#iaV5rsc)"><ellipse transform="rotate(-27.914 13.294 14.538)" class="ctub4ddyk"/><ellipse fill="url(#iInBVJv)" transform="rotate(-27.914 13.294 14.538)" class="ry8stmbsr"/></g><g filter="url(#iCthAAa)"><path stroke="url(#i8hTxzc)" class="k44xquige"/></g><g filter="url(#ii4Vtxc)"><path stroke="url(#i4EaiGb)" class="nzp6ncczm"/></g><defs><radialGradient id="iG4aAJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.92698 0 0 3.37223 8.944 15.392)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ieWtTNd" cx="0" cy="0" r="1" gradientTransform="matrix(.90778 -.661 .75446 1.03612 21.632 15.102)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iykixvb" cx="0" cy="0" r="1" gradientTransform="matrix(.9018 -1.65868 .97083 .52783 21.178 16.294)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="icBB7xb" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -8.103 33.501)scale(.40062 .51644)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iCHp4vb" cx="0" cy="0" r="1" gradientTransform="matrix(.87607 -3.2466 1.20394 .32487 20.762 10.883)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ieHp7me" cx="0" cy="0" r="1" gradientTransform="matrix(4.19996 .3865 -.20782 2.2583 18.958 8.95)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iWvW2Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84386 -2.85562 0 15.99 5.948)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="ivopd5m" cx="0" cy="0" r="1" gradientTransform="matrix(3.37543 -2.4736 3.87532 5.2882 8.91 13.434)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="io8R0nc" cx="0" cy="0" r="1" gradientTransform="matrix(8.8125 0 0 9.43494 11 29.99)" gradientUnits="userSpaceOnUse"><stop class="q920b5bgt"/><stop offset="1" class="hmv6xsb8e"/></radialGradient><radialGradient id="iupWyyd" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -8.62501 6.82131 4.1521 23.375 24.35)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="bawjzlb6r"/><stop offset="1" class="ati7d-krq"/></radialGradient><radialGradient id="irAwi8d" cx="0" cy="0" r="1" gradientTransform="matrix(3 0 0 4.4849 7.5 29.99)" gradientUnits="userSpaceOnUse"><stop class="qe_-3ab1e"/><stop offset="1" class="chsdmobsg"/></radialGradient><radialGradient id="iW1Iv5t" cx="0" cy="0" r="1" gradientTransform="matrix(.87505 5.5 -7.00176 1.11398 15.126 19.538)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gwwxrtb_v"/><stop offset="1" class="ssq48xbfd"/></radialGradient><radialGradient id="inh7lSc" cx="0" cy="0" r="1" gradientTransform="rotate(118.413 2.335 6.065)scale(1.08366 3.24985)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zpk636z_v"/><stop offset="1" class="mtfxop-pk"/></radialGradient><radialGradient id="i8JJXrd" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 0 0 28.1734 1.625 13.788)" gradientUnits="userSpaceOnUse"><stop class="sg9fyvxai"/><stop offset="1" class="r0adxvbzx"/></radialGradient><radialGradient id="imuAEBe" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.68753 -3.8615 2.52917 25.625 5.913)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="t4nmlm7ht"/><stop offset="1" class="q4q53m76f"/></radialGradient><radialGradient id="iSqBlke" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .84375 -2.45037 1.58819 23.657 6.476)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="ubeq2y34d"/><stop offset="1" class="r7flkhbpm"/></radialGradient><radialGradient id="iqPrsTK" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xli568bjl"/><stop offset="1" class="dvyuy-plf"/></radialGradient><radialGradient id="ivdZkMc" cx="0" cy="0" r="1" gradientTransform="rotate(-112.749 16.634 6.815)scale(3.15174 2.83444)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="mqouhz3pk"/><stop offset="1" class="oscm9ub5d"/></radialGradient><radialGradient id="i2QzoZV" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dp3nzmbzl"/><stop offset="1" class="wkrt2mblo"/></radialGradient><radialGradient id="i2vOWDd" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="i0f64nbug"/><stop offset="1" class="ucmtgi-2a"/></radialGradient><radialGradient id="i4Z432d" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.276 6.464)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="xr5reebcs"/><stop offset="1" class="z9wcvylbn"/></radialGradient><radialGradient id="i3nxMBb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.402 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zi5l5kj0o"/><stop offset="1" class="mcuv6-nuk"/></radialGradient><radialGradient id="i9ATG8d" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="xrgskrbeu"/><stop offset="1" class="youzx1gsf"/></radialGradient><radialGradient id="ijFyBlc" cx="0" cy="0" r="1" gradientTransform="matrix(.74502 .76747 -3.62255 3.5166 8.584 3.413)" gradientUnits="userSpaceOnUse"><stop class="i0xt980of"/><stop offset="1" class="n1psrewes"/></radialGradient><radialGradient id="izG65ob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.46 5.257)" gradientUnits="userSpaceOnUse"><stop class="vkm05yehh"/><stop offset=".759" class="mzksnyx6l"/></radialGradient><radialGradient id="iqfRMNF" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="uph7y6b-c"/><stop offset="1" class="ufznmm6ku"/></radialGradient><radialGradient id="i3fcDvw" cx="0" cy="0" r="1" gradientTransform="matrix(-.15093 -1.2516 6.27758 -.757 12.904 3.221)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iMCL7Ep" cx="0" cy="0" r="1" gradientTransform="rotate(55.635 5.044 11.996)scale(4.22355 4.62851)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="dx7h84bsl"/><stop offset=".896" class="e7f2o7b6i"/></radialGradient><radialGradient id="iGBGCYb" cx="0" cy="0" r="1" gradientTransform="matrix(.16688 -1.62542 5.33705 .54795 19.604 3.398)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="i1auEWd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.151 8.864 -5.072)scale(1.21254 6.13593)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iJgax7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.63304 2.73066 -3.00756 1.79864 13.653 1.855)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="ilvOO4b" cx="0" cy="0" r="1" gradientTransform="matrix(.09375 -2.125 7.91564 .34922 18.615 4.3)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="ifw7fHd" cx="0" cy="0" r="1" gradientTransform="matrix(.04203 -1.1037 3.99518 .15214 13.945 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iqbvtPe" cx="0" cy="0" r="1" gradientTransform="rotate(57.127 3.892 14.014)scale(2.59234 3.1316)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="iIu8Rhd" cx="0" cy="0" r="1" gradientTransform="matrix(.01562 -1.15625 4.63352 .06261 18.474 4.522)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="i8nLFcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05908 -1.21917 3.8426 -.1862 13.516 5.64)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iU90igb" cx="0" cy="0" r="1" gradientTransform="rotate(85.073 5.274 8.862)scale(3.92006 3.10284)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="iIpvJFe" cx="0" cy="0" r="1" gradientTransform="matrix(.07604 -1.3001 4.12187 .24108 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="iLjyNhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07831 4.16712 -14.86837 -3.84744 20.85 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="s_7ldyban"/><stop offset="1" class="wuo647bgi"/></radialGradient><radialGradient id="ixYC5Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="gt3x42bpl"/><stop offset="1" class="grtoohbub"/></radialGradient><radialGradient id="iSyDdEe" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="antc_rrkm"/><stop offset="1" class="jqq63xj1b"/></radialGradient><radialGradient id="iOz6e2d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53124 -8.125 5.12798 -2.85982 9.094 24.881)" gradientUnits="userSpaceOnUse"><stop class="x034jqb5d"/><stop offset="1" class="rpjijqwhi"/></radialGradient><radialGradient id="iuC8oHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.625 -13.0654 0 16.022 13.278)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="xlsr65bou"/><stop offset="1" class="s0nym4b3v"/></radialGradient><radialGradient id="i7uQyub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.43528 1.76649 0 18.567 13.996)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="ijXwnhc" cx="0" cy="0" r="1" gradientTransform="scale(1.89931 1.52728)rotate(-90 8.14 1)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iKYWf9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21621 -.69464 0 16.35 17.157)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="irlXONc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89069 -1.41674 0 18.383 14.643)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNH3Nmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2546 -.3281 .4517 -.35053 18.132 14.736)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0rZPze" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89073 -1.41681 0 13.592 14.643)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iInBVJv" cx="0" cy="0" r="1" gradientTransform="matrix(-.0085 -.54242 .652 -.0102 13.278 14.884)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ijFPqje" x1="10.777" x2="10.073" y1="15.698" y2="15.698" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iaQAaRs" x1="22.416" x2="21.517" y1="14.194" y2="16.979" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ireSPNe" x1="10.871" x2="10.871" y1="10.001" y2="12.369" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="i1ryfob" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="b9v5e-b3e"/><stop offset="1" class="t_qwphcjx"/></linearGradient><linearGradient id="i7AyVUc" x1="14.261" x2="10.736" y1="2.588" y2="4.348" gradientUnits="userSpaceOnUse"><stop offset=".565" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iF42OSy" x1="14.299" x2="11.472" y1="2.495" y2="4.331" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="ifXGk1d" x1="16.576" x2="20.718" y1="2.557" y2="4.814" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".704" class="aphqukgtk"/></linearGradient><linearGradient id="ipfeOLc" x1="15.286" x2="12.235" y1="3.297" y2="4.422" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iVmAHha" x1="15.432" x2="12.281" y1="3.185" y2="4.567" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="iG8mdDe" x1="15.545" x2="20.274" y1="3.443" y2="4.831" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="iaB4TJb" x1="14.956" x2="12.465" y1="4.165" y2="5.276" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="i5FFNib" x1="16.265" x2="19.174" y1="4.234" y2="5.677" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="iRHom1b" x1="14.472" x2="11.788" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iLMBJiH" x1="14.505" x2="12.194" y1="5.201" y2="5.924" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="iBjn1Hd" x1="15.088" x2="11.938" y1="4.044" y2="5.427" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="iDQOVwm" x1="16.8" x2="20.02" y1="5.254" y2="6.073" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="ipBmWWm" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="tuzqszfby"/><stop offset="1" class="ljv2-xbix"/></linearGradient><linearGradient id="iE8u6Dc" x1="20.422" x2="12.036" y1="15.82" y2="17.07" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="iTWzvPe" x1="9.794" x2="13.482" y1="17.497" y2="17.622" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="ieG8M5c" x1="10.065" x2="12.131" y1="18.78" y2="18.707" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ixKh99c" x1="15.407" x2="24.349" y1="12.543" y2="9.341" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iPEayOb" x1="15.041" x2="16.072" y1="16.544" y2="16.544" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iZztVzd" x1="17.021" x2="15.895" y1="16.898" y2="16.882" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ixrDqTc" x1="16.204" x2="16.204" y1="17.713" y2="17.084" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="ifwtd1b" x1="16.128" x2="16.128" y1="17.759" y2="17.575" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="i5dsXuB" x1="14.852" x2="15.329" y1="19.487" y2="18.732" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iCJj4vd" x1="19.237" x2="18.893" y1="14.703" y2="14.915" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUMNxni" x1="14.409" x2="14.064" y1="14.703" y2="14.915" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8hTxzc" x1="19.254" x2="18.793" y1="12.353" y2="11.41" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i4EaiGb" x1="13.429" x2="12.123" y1="12.213" y2="11.665" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><filter id="i9PlWXc" width="3.866" height="3.666" x="8.944" y="13.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3730"/></filter><filter id="i4sUQLT" width="3.185" height="3.185" x="9.184" y="13.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".25"/></filter><filter id="iHxIJ4q" width="3.916" height="3.916" x="19.39" y="13.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3730"/></filter><filter id="iYeiHFe" width="3.185" height="3.185" x="19.631" y="13.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".25"/></filter><filter id="itLlu4d" width="13.838" height="9.332" x="9.072" y="5.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3730"/></filter><filter id="iK268ke" width="1.033" height="2.418" x="10.354" y="9.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".125"/></filter><filter id="i5scKHb" width="15.688" height="8.156" x="9.357" y="22.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".375"/></filter><filter id="ijFewce" width="3.938" height="1.28" x="10.688" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".125"/></filter><filter id="iJvoazb" width="3.966" height="1.018" x="11.791" y="2.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".125"/></filter><filter id="igGhk6c" width="2.922" height="1.004" x="11.925" y="4.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".125"/></filter><filter id="iNNKDee" width="3.966" height="1.018" x="11.448" y="3.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".125"/></filter><filter id="iCJDDXc" width="9.632" height="11.909" x="1.844" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".25"/></filter><filter id="iKnM6Ke" width="4.094" height="4.656" x="7.923" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".25"/></filter><filter id="iL68X6b" width="11.391" height="13.458" x="10.326" y="9.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3730"/></filter><filter id="ixbYKgJ" width="8.663" height="7.367" x="14.177" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation="1"/></filter><filter id="i7rWrtc" width="3.433" height="4.444" x="14.012" y="14.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".375"/></filter><filter id="iytyvld" width="2.561" height="3.444" x="14.71" y="14.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".125"/></filter><filter id="ilyRQlc" width="3.247" height="2.017" x="17.289" y="11.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3730"/></filter><filter id="imzBS7c" width="3.248" height="2.017" x="11.636" y="11.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3730"/></filter><filter id="iCCpuUw" width=".844" height=".745" x="17.587" y="14.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".05"/></filter><filter id="iMWurPb" width=".939" height=".964" x="18.519" y="14.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".1"/></filter><filter id="i7wfiTy" width="1.044" height="1.103" x="13.641" y="14.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".1"/></filter><filter id="iaV5rsc" width=".983" height=".754" x="12.803" y="14.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".05"/></filter><filter id="iCthAAa" width="3.531" height="1.973" x="17.064" y="11.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".25"/></filter><filter id="ii4Vtxc" width="3.616" height="2.036" x="11.332" y="11.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3730" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-ok-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.agt7cdzvy {
  stop-color: var(--svg-color--ffd9c8, #FFD9C8);
  stop-opacity: 0;
}

.antc_rrkm {
  stop-color: var(--svg-color--ffc3aa, #FFC3AA);
}

.aphqukgtk {
  stop-color: var(--svg-color--d3a28e, #D3A28E);
  stop-opacity: 0;
}

.ati7d-krq {
  stop-color: var(--svg-color--298dff, #298DFF);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.b9v5e-b3e {
  stop-color: var(--svg-color--3ca8ff, #3CA8FF);
}

.bawjzlb6r {
  stop-color: var(--svg-color--298dff, #298DFF);
}

.bl2yw2f5t {
  stop-color: var(--svg-color--bf876a, #BF876A);
  stop-opacity: 0;
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw3xffbxo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.167 3.374c.43-.109 2.2-.358 3.216-.233");
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.chsdmobsg {
  stop-color: var(--svg-color--499efa, #499EFA);
  stop-opacity: 0;
}

.ci8i_zxyy {
  cx: 21.223px;
  cy: 15.392px;
  r: 1.093px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
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

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
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

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dc7v1rsdf {
  stop-color: var(--svg-color--f4c7b0, #F4C7B0);
  stop-opacity: 0;
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.do-g6qb_k {
  stop-color: var(--svg-color--f4c7b0, #F4C7B0);
}

.dp3nzmbzl {
  stop-color: var(--svg-color--2d99fd, #2D99FD);
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

.dw85flb0t {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.156-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.dx7h84bsl {
  stop-color: var(--svg-color--d09b80, #D09B80);
  stop-opacity: 0;
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7f2o7b6i {
  stop-color: var(--svg-color--d09b80, #D09B80);
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.f_t_65bdv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.612 13.821c.717 0 1.323.495 1.488 1.163a.3.3 0 0 1-.294.374h-2.45a.253.253 0 0 1-.249-.299a1.535 1.535 0 0 1 1.505-1.238");
}

.f0229regj {
  d: path("M7.312 5.365c-.203-.057-.676-.154-.945-.086c-.336.086-.594.329-.812.688c-.175.287-1.47 2.48-2.094 3.539c-.563.823-1.625 3.088-1.375 5.563c.1 1.662.781 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.376-5.563a915 915 0 0 0-2.094-3.54c-.218-.358-.476-.6-.812-.687c-.269-.068-.742.03-.945.086L21.5 7.53c-.352.415-.19.967-.055 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a50 50 0 0 0-1.343-.59c-.295.137-.22.125-.551.175v.29a2.307 2.307 0 1 1-4.615 0v-.384c-.298-.05-.329.076-.593-.043c-.418.155-1.092.472-1.252.552a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.135-.213.297-.765-.055-1.18z");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fawmdr3-g {
  stop-color: var(--svg-color--d29d82, #D29D82);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g7mweqbwu {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m20.075 12.406l-.002-.001l-.002-.002l-.005-.004l-.013-.01a2 2 0 0 0-.17-.119a3 3 0 0 0-.46-.231a3.1 3.1 0 0 0-1.64-.174a.586.586 0 0 0 .183 1.158a1.9 1.9 0 0 1 1.025.106a1.7 1.7 0 0 1 .33.175l.009.006a.586.586 0 0 0 .745-.904");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ggskh2bzm {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.156 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.grtoohbub {
  stop-color: var(--svg-color--ce9488, #CE9488);
  stop-opacity: 0;
}

.gt3x42bpl {
  stop-color: var(--svg-color--ce9488, #CE9488);
}

.gwwxrtb_v {
  stop-color: var(--svg-color--1d5894, #1D5894);
}

.h12lzabje {
  d: path("m21.282 8.28l.471.234c.825.41 1.296 1.347 1.12 2.342l-.649 3.338c-.057.345-.285.577-.628.586h-.02s.06-.996.118-1.581c.048-.476-.035-.62-.471-1.054c-.236-.235-.412-.586-.412-.937v-.937c0-.293-.236-.528-.471-.586c-.707-.176-2.18-.469-4.3-.469s-3.593.293-4.3.469a.57.57 0 0 0-.471.585v.938c0 .35-.118.702-.412.937l-.177.175c-.236.176-.354.527-.354.82c.06.644.118 1.581.118 1.581l-.054-.001a.695.695 0 0 1-.653-.584l-.647-3.338c-.118-.937.353-1.874 1.178-2.284l.47-.235c.295-.175.59-.41.884-.644l1.06-1.113c.648-.585 1.59-.761 2.415-.351a3.23 3.23 0 0 0 1.826 0c.884-.293 1.885-.059 2.592.586l.883.878c.236.293.53.469.884.644");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
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

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.i0xt980of {
  stop-color: var(--svg-color--d9ab8f, #D9AB8F);
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

.iziaq4wdz {
  stop-color: var(--svg-color--d29d82, #D29D82);
  stop-opacity: 0;
}

.jh3kajxvi {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.jqq63xj1b {
  stop-color: var(--svg-color--ffc3aa, #FFC3AA);
  stop-opacity: 0;
}

.k44xquige {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.814 12.247c.472-.083 1.393-.06 2.03.437");
}

.kac_i9wmf {
  d: path("M10.326 13.14c0-.293.118-.644.354-.82l.177-.175c.294-.235.412-.586.412-.937v-.937a.57.57 0 0 1 .471-.586c.707-.176 2.18-.469 4.3-.469s3.593.293 4.3.469c.235.058.47.293.47.585v.938c0 .35.177.702.413.937c.551.386.517.598.471 1.054a51 51 0 0 0-.118 1.581h.02l-.292 4.346c-.176 1.944-1.703 3.298-3.525 3.298h-3.525c-1.88 0-3.35-1.354-3.525-3.298c-.153-1.994-.22-3.995-.403-5.986");
}

.kj76vd-0e {
  d: path("m20.343 9.216l-3.38 1.127a1.15 1.15 0 0 0 .517 2.23l3.36-.45z");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc0lwfbjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
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

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lucf2ebsd {
  cx: 21.223px;
  cy: 15.392px;
  r: 1.833px;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcuv6-nuk {
  stop-color: var(--svg-color--4298d4, #4298D4);
  stop-opacity: 0;
}

.mjj8sabfd {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.57 15.08l-.583 1.865a.592.592 0 0 0 .572.768h.863c.405 0 .69-.39.572-.768l-.584-1.866c-.125-.413-.708-.413-.84 0");
}

.mqouhz3pk {
  stop-color: var(--svg-color--f2c3b4, #F2C3B4);
}

.mtfxop-pk {
  stop-color: var(--svg-color--43bbff, #43BBFF);
  stop-opacity: 0;
}

.mzksnyx6l {
  stop-color: var(--svg-color--f4c7ad, #F4C7AD);
}

.n1psrewes {
  stop-color: var(--svg-color--d9ab8f, #D9AB8F);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nb53z0s7p {
  fill: var(--svg-color--000, #000);
  d: path("M17.824 15.1c0-.312.25-.561.561-.561a.56.56 0 0 1 .499.819h-.993a.5.5 0 0 1-.067-.258");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nzp6ncczm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.082 12.816c.36-.317 1.144-.652 2.117-.497");
}

.o4lj9bc9c {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oscm9ub5d {
  stop-color: var(--svg-color--be8c8a, #BE8C8A);
}

.ouf_rrb9s {
  d: path("M18.313 14.327c.07.093-.076.207-.242.331s-.289.212-.359.118c-.07-.093.008-.27.174-.393c.166-.124.357-.15.427-.056");
}

.oz8qvprqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.pcn7dpbez {
  d: path("M19.258 14.97a.92.92 0 0 0-.254-.507l-.285.313l.128.25z");
}

.pf8qhd_wg {
  fill: var(--svg-color--242324, #242324);
  d: path("m21.282 8.28l.471.234c.825.41 1.296 1.347 1.12 2.342l-.649 3.338c-.057.345-.285.577-.628.586h-.02s.06-.996.118-1.581c.048-.476-.035-.62-.471-1.054c-.236-.235-.412-.586-.412-.937v-.937c0-.293-.236-.528-.471-.586c-.707-.176-2.18-.469-4.3-.469s-3.593.293-4.3.469a.57.57 0 0 0-.471.585v.938c0 .35-.118.702-.412.937l-.177.175c-.236.176-.354.527-.354.82c.06.644.118 1.581.118 1.581l-.054-.001a.695.695 0 0 1-.653-.584l-.647-3.338c-.118-.937.353-1.874 1.178-2.284l.47-.235c.295-.175.59-.41.884-.644l1.06-1.113c.648-.585 1.59-.761 2.415-.351a3.23 3.23 0 0 0 1.826 0c.884-.293 1.885-.059 2.592.586l.883.878c.236.293.53.469.884.644");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psmqb459k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.064 3.03c.68-.344 2.468-.57 3.187-.524");
}

.pwg4g4b6s {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q2kzydr5a {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.847 12.406l.002-.002l.005-.004l.013-.01a2 2 0 0 1 .17-.119a3 3 0 0 1 .461-.231a3.1 3.1 0 0 1 1.64-.174a.586.586 0 1 1-.183 1.158a1.94 1.94 0 0 0-1.026.106a1.7 1.7 0 0 0-.33.175l-.008.006a.586.586 0 0 1-.745-.904");
}

.q4q53m76f {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
  stop-opacity: 0;
}

.q920b5bgt {
  stop-color: var(--svg-color--2691ff, #2691FF);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qe_-3ab1e {
  stop-color: var(--svg-color--499efa, #499EFA);
}

.qq92qrb7u {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.493 18.424a.22.22 0 0 0-.26.045a.2.2 0 0 0-.022.257c.376.57 1.032.95 1.78.95c.746 0 1.403-.38 1.78-.95a.2.2 0 0 0-.023-.26a.22.22 0 0 0-.26-.042a3.2 3.2 0 0 1-1.498.355a3.25 3.25 0 0 1-1.498-.355Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r0adxvbzx {
  stop-color: var(--svg-color--54acf3, #54ACF3);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r7flkhbpm {
  stop-color: var(--svg-color--419ae2, #419AE2);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rg-7ehwto {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.688 15.258l-.9 1.867c-.112.383.156.767.535.767h.81c.38 0 .647-.39.536-.767l-.547-1.867c-.118-.413-.311-.413-.434 0");
}

.rl4irpj3j {
  d: path("M7.788 26.79L2.344 16.695l4.594-.812l4.038 7.877c-1.35 2.025-2.688 2.865-3.188 3.032");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rpjijqwhi {
  stop-color: var(--svg-color--2882ff, #2882FF);
  stop-opacity: 0;
}

.rtl5cbcmo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.363 13.821c-.717 0-1.323.495-1.488 1.163a.3.3 0 0 0 .294.374h2.45c.155 0 .28-.143.25-.299a1.54 1.54 0 0 0-1.506-1.238");
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.ry8stmbsr {
  cx: 13.294px;
  cy: 14.538px;
  rx: 0.428px;
  ry: 0.216px;
}

.s_7ldyban {
  stop-color: var(--svg-color--cd978c, #CD978C);
  stop-opacity: 0;
}

.s0nym4b3v {
  stop-color: var(--svg-color--a77d91, #A77D91);
}

.s45c4_k9i {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
}

.s59e5ab9a {
  stop-color: var(--svg-color--d3a28e, #D3A28E);
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sg9fyvxai {
  stop-color: var(--svg-color--54acf3, #54ACF3);
}

.ssq48xbfd {
  stop-color: var(--svg-color--1d5894, #1D5894);
  stop-opacity: 0;
}

.t_qwphcjx {
  stop-color: var(--svg-color--2a99ff, #2A99FF);
}

.t4nmlm7ht {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
}

.tdjdjpb5y {
  d: path("M18.385 14.12a.98.98 0 0 1 .944 1.238h-1.892a.984.984 0 0 1 .949-1.238");
}

.tmlw0f1oe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.013 10.11v.985c-.009.163-.077.528-.284.683");
}

.tuzqszfby {
  stop-color: var(--svg-color--3a95fa, #3A95FA);
}

.u_sj9acab {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.313 14.327c.07.093-.076.207-.242.331s-.289.212-.359.118c-.07-.093.008-.27.174-.393c.166-.124.357-.15.427-.056");
}

.u5as6fnzn {
  d: path("M13.59 14.12a.98.98 0 0 0-.944 1.238h1.892q.035-.127.036-.258a.986.986 0 0 0-.984-.98");
}

.ubeq2y34d {
  stop-color: var(--svg-color--419ae2, #419AE2);
}

.ucmtgi-2a {
  stop-color: var(--svg-color--49abff, #49ABFF);
  stop-opacity: 0;
}

.ufznmm6ku {
  stop-color: var(--svg-color--d3aa91, #D3AA91);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uph7y6b-c {
  stop-color: var(--svg-color--d3aa91, #D3AA91);
}

.uu85wsbky {
  cx: 10.777px;
  cy: 15.392px;
  r: 1.093px;
}

.v5ht5gbjt {
  fill: var(--svg-color--000, #000);
  d: path("M14.151 15.1a.56.56 0 0 0-.561-.562a.56.56 0 0 0-.499.82h.993a.56.56 0 0 0 .067-.258");
}

.vkm05yehh {
  stop-color: var(--svg-color--ffdabd, #FFDABD);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vzv6bacbx {
  stop-color: var(--svg-color--bf876a, #BF876A);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
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

.wkrt2mblo {
  stop-color: var(--svg-color--1284d5, #1284D5);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wuo647bgi {
  stop-color: var(--svg-color--a97265, #A97265);
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x034jqb5d {
  stop-color: var(--svg-color--2882ff, #2882FF);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xl-zenb2y {
  stop-color: var(--svg-color--ffd9c8, #FFD9C8);
}

.xli568bjl {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
}

.xlsr65bou {
  stop-color: var(--svg-color--e0ad9b, #E0AD9B);
  stop-opacity: 0;
}

.xr5reebcs {
  stop-color: var(--svg-color--4bb4ff, #4BB4FF);
}

.xra9oc37j {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
  stop-opacity: 0;
}

.xrgskrbeu {
  stop-color: var(--svg-color--fcc4ac, #FCC4AC);
}

.xv1wl_b5e {
  cx: 21.223px;
  cy: 15.392px;
  r: 1.093px;
}

.y0hurf_aa {
  d: path("M14.485 14.985c0-.317-.258-.528-.327-.592l-.317.306l.195.397z");
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.youzx1gsf {
  stop-color: var(--svg-color--edc1a6, #EDC1A6);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z9wcvylbn {
  stop-color: var(--svg-color--347bc6, #347BC6);
}

.zeplyxbfk {
  d: path("m15.57 15.08l-.583 1.865a.592.592 0 0 0 .572.768h.863c.405 0 .69-.39.572-.768l-.584-1.866c-.125-.413-.708-.413-.84 0");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zi5l5kj0o {
  stop-color: var(--svg-color--4298d4, #4298D4);
}

.zoy4bqbmr {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.zpk636z_v {
  stop-color: var(--svg-color--43bbff, #43BBFF);
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
