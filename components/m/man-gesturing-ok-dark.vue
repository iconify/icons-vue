<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iL5o1oH" class="mdbc_mbcb"/></defs><g class="ft5dv1b6b"><g filter="url(#inCSFGd)"><circle fill="url(#icZS6vc)" class="grjy2ibxl"/></g><g filter="url(#iXYGlbe)"><circle fill="url(#i8UuUOe)" class="alz6ou_yx"/></g><g filter="url(#iCOduwb)"><circle fill="url(#iuS2rUb)" class="dkx1nably"/><circle fill="url(#iV6Hgeb)" class="dkx1nably"/></g><g filter="url(#i14u7Gc)"><circle class="bjhw35ewa"/><circle fill="url(#iV5Flbc)" class="f6gi-_2ps"/><circle fill="url(#iEyB3yc)" class="f6gi-_2ps"/></g><g filter="url(#i4OvGve)"><path class="a-1whnb6d"/><path fill="url(#ijGTvlb)" class="frw02xb6z"/><path fill="url(#iqpwSHd)" class="frw02xb6z"/><path fill="url(#iVk73Oc)" class="frw02xb6z"/><path fill="url(#iBl4KHD)" class="frw02xb6z"/></g><path fill="url(#i1ryfob)" class="f0229regj"/><path fill="url(#io8R0nc)" class="f0229regj"/><path fill="url(#iupWyyd)" class="f0229regj"/><path fill="url(#irAwi8d)" class="f0229regj"/><path fill="url(#iW1Iv5t)" class="f0229regj"/><path fill="url(#inh7lSc)" class="f0229regj"/><path fill="url(#i8JJXrd)" class="f0229regj"/><path fill="url(#imuAEBe)" class="f0229regj"/><path fill="url(#iSqBlke)" class="f0229regj"/><g filter="url(#iHqlhCU)"><path fill="url(#iqPrsTK)" class="x_mri4gas"/></g><rect fill="url(#iFa2gBh)" class="iuxb-78iw"/><path fill="url(#i2QzoZV)" class="veix-z38b"/><path fill="url(#i2vOWDd)" class="veix-z38b"/><path fill="url(#i4Z432d)" class="ygsync4_o"/><path fill="url(#ivztzoe)" class="ygsync4_o"/><path fill="url(#iHW23Gc)" class="r_9_ioa3h"/><path fill="url(#iUaTakc)" class="r_9_ioa3h"/><path fill="url(#iBW95Ad)" class="eim_mrbrv"/><path fill="url(#icK1TWc)" class="eim_mrbrv"/><path class="fd_orqb8o"/><path stroke="url(#i66AH3c)" class="djebsbcjo"/><path stroke="url(#ieShG0d)" class="djebsbcjo"/><g filter="url(#iV3s4re)"><path stroke="url(#igwtotc)" class="psmqb459k"/></g><path stroke="url(#if9JlAb)" class="w930jqbym"/><path stroke="url(#ikDe6mb)" class="w930jqbym"/><path stroke="url(#ieO98ab)" class="w930jqbym"/><path stroke="url(#iMRszjb)" class="w930jqbym"/><path class="idef6gfar"/><path stroke="url(#iufEA5d)" class="cvtf9k6wz"/><path stroke="url(#i4Dl8Id)" class="cvtf9k6wz"/><g filter="url(#iPpVlZd)"><path stroke="url(#isUy3jd)" class="bw3xffbxo"/></g><path stroke="url(#i9be0ZL)" class="lc0lwfbjp"/><path stroke="url(#ikEUioc)" class="lc0lwfbjp"/><path stroke="url(#i8GxwYc)" class="lc0lwfbjp"/><path stroke="url(#iWw1pcb)" class="lc0lwfbjp"/><use href="#iL5o1oH" class="exlknac3d"/><path stroke="url(#i5NYVmc)" class="zw6cmm23y"/><path stroke="url(#i0C0K2d)" class="zw6cmm23y"/><use href="#iL5o1oH" class="exlknac3d"/><path stroke="url(#i5NYVmc)" class="zw6cmm23y"/><path stroke="url(#i0C0K2d)" class="zw6cmm23y"/><path stroke="url(#i3B38ob)" class="abd3-ibar"/><path stroke="url(#iSD4mwe)" class="abd3-ibar"/><path stroke="url(#i5qddYb)" class="abd3-ibar"/><path stroke="url(#iJlii9q)" class="abd3-ibar"/><path class="s68j-sb_c"/><path stroke="url(#i9zbruc)" class="hockzyb4d"/><g filter="url(#i9SOREb)"><path stroke="url(#id1Hxsd)" class="oz8qvprqg"/></g><g filter="url(#ijaXQCb)"><path stroke="url(#iK2Zivb)" class="drig65bxb"/></g><path stroke="url(#i3sOJ7d)" class="lgc2wbcpd"/><path stroke="url(#iQsfHle)" class="lgc2wbcpd"/><path fill="url(#idkSmhJ)" class="eim_mrbrv"/><path fill="url(#iVm4I3c)" class="eim_mrbrv"/><path fill="url(#iMQr3Cm)" class="r_9_ioa3h"/><path fill="url(#iw1Rh0J)" class="r_9_ioa3h"/><g filter="url(#ihtoVne)"><path fill="url(#iOz6e2d)" class="rl4irpj3j"/></g><g filter="url(#ivnLcfe)"><path stroke="url(#ipBmWWm)" class="id0lipbed"/></g><g filter="url(#ibUoXdc)"><path fill="url(#i6paUeb)" class="zoki_jbgf"/><path fill="url(#ihzpjje)" class="zoki_jbgf"/><path fill="url(#iEsFelC)" class="zoki_jbgf"/><path fill="url(#ic7SIgb)" class="zoki_jbgf"/><path fill="url(#iYP8FUb)" class="zoki_jbgf"/><path fill="url(#ibUqxlb)" class="zoki_jbgf"/></g><g filter="url(#i4vCi3c)"><path fill="url(#iEXyJMc)" class="ikjh3ionc"/></g><g filter="url(#i4KzIxQ)"><path class="lckvribwd"/></g><g filter="url(#ixS2qpd)"><path class="kwqh1abfs"/><path fill="url(#iRyg5md)" class="kgldmvbwx"/><path fill="url(#ikQNGBO)" class="kgldmvbwx"/><path fill="url(#iytjzjZ)" class="kgldmvbwx"/><path fill="url(#ioU9pdd)" class="kgldmvbwx"/></g><path fill="url(#iSLhHnb)" class="kgldmvbwx"/><path stroke="url(#iFPkgxd)" class="vsxiggb-z"/><g filter="url(#i3fQTQd)"><path class="q32ba3wcl"/></g><g filter="url(#iruVAdc)"><path class="fimazrbie"/></g><path class="fi6zpub0i"/><path fill="url(#iAP5cTd)" class="sv-2dkb_f"/><path class="lcts4tbut"/><g filter="url(#iFjJkyb)"><path class="gevp4whvm"/><path fill="url(#ibe9lqc)" class="zbtcl2bba"/></g><g filter="url(#ics6xic)"><path fill="url(#impqYDM)" class="vg834-1ys"/></g><path class="uq-5i0dud"/><path fill="url(#ivPsJ0d)" class="uj4h67pks"/><path class="ryjfaggzx"/><g filter="url(#iVWMLJe)"><path fill="url(#iih1jDe)" class="r-iyesm5a"/></g><g filter="url(#iCJa5Ub)"><ellipse transform="rotate(-27.914 13.36 14.454)" class="j92tbybrc"/><ellipse fill="url(#itg1Uxe)" transform="rotate(-27.914 13.36 14.454)" class="n4l_fgb1u"/></g><g filter="url(#iGHp6je)"><path stroke="url(#iKWCzlF)" class="m8b0uf44i"/></g><g filter="url(#iWnat9c)"><path stroke="url(#iGOMq0c)" class="ad-wu5bwf"/></g><g filter="url(#iW3aUQd)"><path stroke="url(#ipyhGLd)" class="gb3ua4f-n"/></g><defs><radialGradient id="icZS6vc" cx="0" cy="0" r="1" gradientTransform="matrix(1.87996 0 0 3.28995 9.116 15.287)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iV6Hgeb" cx="0" cy="0" r="1" gradientTransform="matrix(.88564 -.64488 .73604 1.01084 21.494 15.004)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iV5Flbc" cx="0" cy="0" r="1" gradientTransform="matrix(.87982 -1.6182 .94714 .51496 21.051 16.167)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iEyB3yc" cx="0" cy="0" r="1" gradientTransform="matrix(.27777 .27495 -.35446 .35809 21.095 15.288)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ijGTvlb" cx="0" cy="0" r="1" gradientTransform="matrix(.85469 -3.16738 1.17457 .31695 20.646 10.888)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iqpwSHd" cx="0" cy="0" r="1" gradientTransform="matrix(4.09749 .37707 -.20275 2.2032 18.886 9.003)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iVk73Oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79888 -2.78595 0 15.99 6.073)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iBl4KHD" cx="0" cy="0" r="1" gradientTransform="matrix(3.29307 -2.41325 3.78078 5.15916 9.082 13.377)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="io8R0nc" cx="0" cy="0" r="1" gradientTransform="matrix(8.8125 0 0 9.43494 11 29.99)" gradientUnits="userSpaceOnUse"><stop class="q920b5bgt"/><stop offset="1" class="hmv6xsb8e"/></radialGradient><radialGradient id="iupWyyd" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -8.62501 6.82131 4.1521 23.375 24.35)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="bawjzlb6r"/><stop offset="1" class="ati7d-krq"/></radialGradient><radialGradient id="irAwi8d" cx="0" cy="0" r="1" gradientTransform="matrix(3 0 0 4.4849 7.5 29.99)" gradientUnits="userSpaceOnUse"><stop class="qe_-3ab1e"/><stop offset="1" class="chsdmobsg"/></radialGradient><radialGradient id="iW1Iv5t" cx="0" cy="0" r="1" gradientTransform="matrix(.87505 5.5 -7.00176 1.11398 15.126 19.538)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gwwxrtb_v"/><stop offset="1" class="ssq48xbfd"/></radialGradient><radialGradient id="inh7lSc" cx="0" cy="0" r="1" gradientTransform="rotate(118.413 2.335 6.065)scale(1.08366 3.24985)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zpk636z_v"/><stop offset="1" class="mtfxop-pk"/></radialGradient><radialGradient id="i8JJXrd" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 0 0 28.1734 1.625 13.788)" gradientUnits="userSpaceOnUse"><stop class="sg9fyvxai"/><stop offset="1" class="r0adxvbzx"/></radialGradient><radialGradient id="imuAEBe" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.68753 -3.8615 2.52917 25.625 5.913)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="t4nmlm7ht"/><stop offset="1" class="q4q53m76f"/></radialGradient><radialGradient id="iSqBlke" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .84375 -2.45037 1.58819 23.657 6.476)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="ubeq2y34d"/><stop offset="1" class="r7flkhbpm"/></radialGradient><radialGradient id="iqPrsTK" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xli568bjl"/><stop offset="1" class="dvyuy-plf"/></radialGradient><radialGradient id="iFa2gBh" cx="0" cy="0" r="1" gradientTransform="rotate(-129.643 14.383 8.104)scale(3.73397 4.5453)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="yzvp5u7xf"/><stop offset="1" class="jqrkc7szc"/></radialGradient><radialGradient id="i2QzoZV" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dp3nzmbzl"/><stop offset="1" class="wkrt2mblo"/></radialGradient><radialGradient id="i2vOWDd" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="i0f64nbug"/><stop offset="1" class="ucmtgi-2a"/></radialGradient><radialGradient id="i4Z432d" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.276 6.464)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="xr5reebcs"/><stop offset="1" class="z9wcvylbn"/></radialGradient><radialGradient id="ivztzoe" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.401 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zi5l5kj0o"/><stop offset="1" class="mcuv6-nuk"/></radialGradient><radialGradient id="iHW23Gc" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="sjcrub2lh"/><stop offset="1" class="wgkuwteff"/></radialGradient><radialGradient id="iUaTakc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.078 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="wfxtb3qbv"/><stop offset="1" class="eax729dsn"/></radialGradient><radialGradient id="iBW95Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.389)" gradientUnits="userSpaceOnUse"><stop class="v99wjxblu"/><stop offset=".469" class="fve8fmbgh"/></radialGradient><radialGradient id="icK1TWc" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="pa_nigs1j"/><stop offset="1" class="igdnfmbpz"/></radialGradient><radialGradient id="i66AH3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2142 -2.07063 5.3651 -.555 12.766 3.92)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="ieShG0d" cx="0" cy="0" r="1" gradientTransform="matrix(2.11795 2.22809 -3.41166 3.24302 12.504 1.407)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="ieO98ab" cx="0" cy="0" r="1" gradientTransform="rotate(96.911 7.948 9.531)scale(.2597 1.09361)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iMRszjb" cx="0" cy="0" r="1" gradientTransform="matrix(.14465 -1.10153 3.9101 .51345 19.603 3.254)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="iufEA5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.91565 5.00841 0 13.953 4.157)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="snh9c8fxs"/><stop offset=".951" class="y-9i83_gz"/></radialGradient><radialGradient id="i4Dl8Id" cx="0" cy="0" r="1" gradientTransform="matrix(1.57086 2.47251 -3.5045 2.22651 13.953 2.174)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="i8GxwYc" cx="0" cy="0" r="1" gradientTransform="matrix(.03363 .53517 -1.63373 .10266 17.773 3.855)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iWw1pcb" cx="0" cy="0" r="1" gradientTransform="matrix(.05835 -1.56885 4.81421 .17906 18.499 4.07)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="i5NYVmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36455 4.31533 0 13.808 4.777)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="i0C0K2d" cx="0" cy="0" r="1" gradientTransform="rotate(52.458 3.489 15.695)scale(2.22121 3.36062)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="i5qddYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.008 .32792 -1.41492 -.03451 17.966 4.614)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iJlii9q" cx="0" cy="0" r="1" gradientTransform="matrix(.0445 -1.1349 5.86959 .23018 18.412 4.578)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="i9zbruc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06965 -1.61842 4.37527 -.1883 13.456 6.063)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="idkSmhJ" cx="0" cy="0" r="1" gradientTransform="rotate(108.623 9.676 9.169)scale(4.23839 15.1226)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nnha85vdf"/><stop offset="1" class="ttw1-g7zn"/></radialGradient><radialGradient id="iVm4I3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.50682 -3.31996 -1.79016 22.82 2.882)" gradientUnits="userSpaceOnUse"><stop class="h6orixb7r"/><stop offset="1" class="s3qs9xb1s"/></radialGradient><radialGradient id="iMQr3Cm" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="c2b4j9bss"/><stop offset="1" class="rjn5j4bgi"/></radialGradient><radialGradient id="iw1Rh0J" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="f_gowxnlh"/><stop offset="1" class="bx7a6gbyw"/></radialGradient><radialGradient id="iOz6e2d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53124 -8.125 5.12798 -2.85982 9.094 24.881)" gradientUnits="userSpaceOnUse"><stop class="x034jqb5d"/><stop offset="1" class="rpjijqwhi"/></radialGradient><radialGradient id="iEsFelC" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61165 -10.3324 0 15.668 15.074)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="ic7SIgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40026 1.72339 0 18.504 13.925)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iYP8FUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.49002 1.85297 0 13.62 13.89)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ioU9pdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21094 -.67769 0 16.341 17.009)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iAP5cTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .86895 -1.38217 0 18.325 14.557)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibe9lqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2481 -.3197 .44016 -.34157 18.08 14.647)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivPsJ0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .869 -1.38224 0 13.65 14.557)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itg1Uxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00828 -.52856 .63534 -.00995 13.343 14.791)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i8UuUOe" x1="10.904" x2="10.218" y1="15.586" y2="15.586" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iuS2rUb" x1="22.26" x2="21.383" y1="14.118" y2="16.835" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="i1ryfob" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="b9v5e-b3e"/><stop offset="1" class="t_qwphcjx"/></linearGradient><linearGradient id="igwtotc" x1="14.299" x2="11.472" y1="2.495" y2="4.331" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="if9JlAb" x1="18.218" x2="20.905" y1="2.499" y2="3.267" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="ikDe6mb" x1="16.407" x2="18.647" y1="2.657" y2="3.347" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="isUy3jd" x1="14.873" x2="12.389" y1="3.238" y2="4.489" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="i9be0ZL" x1="17.183" x2="20.001" y1="3.104" y2="3.444" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="ikEUioc" x1="15.386" x2="17.749" y1="3.608" y2="3.929" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="i3B38ob" x1="17.421" x2="19.358" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="iSD4mwe" x1="16.007" x2="18.172" y1="5.134" y2="5.083" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="id1Hxsd" x1="14.505" x2="12.194" y1="5.201" y2="5.924" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="iK2Zivb" x1="14.529" x2="12.046" y1="4.097" y2="5.349" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="i3sOJ7d" x1="17.894" x2="19.781" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="iQsfHle" x1="16.55" x2="18.448" y1="5.886" y2="5.719" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset=".84" class="h2thr5bul"/></linearGradient><linearGradient id="ipBmWWm" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="tuzqszfby"/><stop offset="1" class="ljv2-xbix"/></linearGradient><linearGradient id="i6paUeb" x1="20.314" x2="12.133" y1="15.705" y2="16.924" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="ihzpjje" x1="10.21" x2="12.226" y1="18.593" y2="18.521" gradientUnits="userSpaceOnUse"><stop class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="ibUqxlb" x1="16.021" x2="16.021" y1="-1.729" y2="22.363" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="iEXyJMc" x1="15.421" x2="24.146" y1="12.507" y2="9.383" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iRyg5md" x1="15.065" x2="16.07" y1="16.411" y2="16.411" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ikQNGBO" x1="16.996" x2="15.897" y1="16.756" y2="16.741" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iytjzjZ" x1="16.199" x2="16.199" y1="17.552" y2="16.938" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iSLhHnb" x1="16.125" x2="16.125" y1="17.596" y2="17.417" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iFPkgxd" x1="14.88" x2="15.346" y1="19.282" y2="18.545" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="impqYDM" x1="19.157" x2="18.822" y1="14.614" y2="14.821" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iih1jDe" x1="14.447" x2="14.111" y1="14.614" y2="14.821" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKWCzlF" x1="19.175" x2="18.725" y1="12.322" y2="11.402" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iGOMq0c" x1="13.492" x2="12.218" y1="12.185" y2="11.651" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ipyhGLd" x1="10.996" x2="10.996" y1="10.027" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><filter id="inCSFGd" width="3.777" height="3.577" x="9.116" y="13.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3718"/></filter><filter id="iXYGlbe" width="3.132" height="3.132" x="9.338" y="13.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".25"/></filter><filter id="iCOduwb" width="3.827" height="3.827" x="19.307" y="13.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3718"/></filter><filter id="i14u7Gc" width="3.132" height="3.132" x="19.53" y="13.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".25"/></filter><filter id="i4OvGve" width="13.5" height="9.117" x="9.241" y="5.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3718"/></filter><filter id="iHqlhCU" width="15.688" height="8.156" x="9.357" y="22.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".375"/></filter><filter id="iV3s4re" width="3.938" height="1.28" x="10.688" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".125"/></filter><filter id="iPpVlZd" width="3.966" height="1.018" x="11.791" y="2.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".125"/></filter><filter id="i9SOREb" width="2.922" height="1.004" x="11.925" y="4.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".125"/></filter><filter id="ijaXQCb" width="3.966" height="1.018" x="11.448" y="3.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".125"/></filter><filter id="ihtoVne" width="9.632" height="11.909" x="1.844" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".25"/></filter><filter id="ivnLcfe" width="4.094" height="4.656" x="7.923" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".25"/></filter><filter id="ibUoXdc" width="11.113" height="13.135" x="10.465" y="9.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3718"/></filter><filter id="i4vCi3c" width="8.549" height="7.285" x="14.173" y="7.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation="1"/></filter><filter id="i4KzIxQ" width="3.385" height="4.372" x="14.042" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".375"/></filter><filter id="ixS2qpd" width="2.511" height="3.372" x="14.735" y="14.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".125"/></filter><filter id="i3fQTQd" width="3.174" height="1.978" x="17.257" y="11.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3718"/></filter><filter id="iruVAdc" width="3.174" height="1.978" x="11.742" y="11.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3718"/></filter><filter id="iFjJkyb" width=".828" height=".731" x="17.546" y="14.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".05"/></filter><filter id="ics6xic" width=".926" height=".949" x="18.452" y="14.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".1"/></filter><filter id="iVWMLJe" width="1.027" height="1.085" x="13.694" y="14.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".1"/></filter><filter id="iCJa5Ub" width=".963" height=".74" x="12.878" y="14.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".05"/></filter><filter id="iGHp6je" width="3.481" height="1.962" x="17.02" y="11.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".25"/></filter><filter id="iWnat9c" width="3.565" height="2.023" x="11.428" y="11.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".25"/></filter><filter id="iW3aUQd" width="1.026" height="2.377" x="10.483" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3718" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-ok-dark" /></template>
<style>
.a-1whnb6d {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m21.153 8.348l.46.228c.804.4 1.264 1.314 1.092 2.286l-.632 3.256c-.057.337-.28.563-.613.572h-.02s.058-.971.115-1.543c.047-.464-.034-.605-.46-1.028c-.23-.229-.402-.572-.402-.914v-.915c0-.285-.23-.514-.46-.571c-.689-.171-2.125-.457-4.194-.457s-3.505.286-4.195.457a.56.56 0 0 0-.46.571v.915c0 .342-.115.685-.402.914l-.172.171c-.23.172-.345.514-.345.8c.057.629.115 1.543.115 1.543q-.027 0-.053-.002a.68.68 0 0 1-.637-.57l-.632-3.256c-.115-.915.345-1.829 1.15-2.229l.46-.228c.287-.172.574-.4.861-.629l1.035-1.085c.632-.572 1.551-.743 2.356-.343a3.15 3.15 0 0 0 1.78 0c.863-.286 1.84-.057 2.53.571l.861.857c.23.286.517.457.862.629");
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ad-wu5bwf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.178 12.774c.35-.31 1.116-.636 2.065-.485");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.alz6ou_yx {
  cx: 10.904px;
  cy: 15.287px;
  r: 1.066px;
}

.ati7d-krq {
  stop-color: var(--svg-color--298dff, #298DFF);
  stop-opacity: 0;
}

.aypdg85ht {
  stop-color: var(--svg-color--261111, #261111);
  stop-opacity: 0;
}

.b9v5e-b3e {
  stop-color: var(--svg-color--3ca8ff, #3CA8FF);
}

.bawjzlb6r {
  stop-color: var(--svg-color--298dff, #298DFF);
}

.bbijeebsz {
  stop-color: var(--svg-color--261111, #261111);
}

.bcjkesbyj {
  stop-color: var(--svg-color--2d1717, #2D1717);
}

.bjhw35ewa {
  cx: 21.096px;
  cy: 15.287px;
  r: 1.066px;
  fill: var(--svg-color--463133, #463133);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bw3xffbxo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.167 3.374c.43-.109 2.2-.358 3.216-.233");
}

.bx7a6gbyw {
  stop-color: var(--svg-color--533d3d, #533D3D);
  stop-opacity: 0;
}

.c2b4j9bss {
  stop-color: var(--svg-color--30171b, #30171B);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.chsdmobsg {
  stop-color: var(--svg-color--499efa, #499EFA);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvtf9k6wz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dkx1nably {
  cx: 21.096px;
  cy: 15.287px;
  r: 1.788px;
}

.dp3nzmbzl {
  stop-color: var(--svg-color--2d99fd, #2D99FD);
}

.drig65bxb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.823 4.234c.43-.11 2.2-.359 3.216-.234");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dvyuy-plf {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eax729dsn {
  stop-color: var(--svg-color--4e4240, #4E4240);
  stop-opacity: 0;
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.exlknac3d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
}

.f_gowxnlh {
  stop-color: var(--svg-color--533d3d, #533D3D);
}

.f0229regj {
  d: path("M7.312 5.365c-.203-.057-.676-.154-.945-.086c-.336.086-.594.329-.812.688c-.175.287-1.47 2.48-2.094 3.539c-.563.823-1.625 3.088-1.375 5.563c.1 1.662.781 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.376-5.563a915 915 0 0 0-2.094-3.54c-.218-.358-.476-.6-.812-.687c-.269-.068-.742.03-.945.086L21.5 7.53c-.352.415-.19.967-.055 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a50 50 0 0 0-1.343-.59c-.295.137-.22.125-.551.175v.29a2.307 2.307 0 1 1-4.615 0v-.384c-.298-.05-.329.076-.593-.043c-.418.155-1.092.472-1.252.552a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.135-.213.297-.765-.055-1.18z");
}

.f6gi-_2ps {
  cx: 21.096px;
  cy: 15.287px;
  r: 1.066px;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fd_orqb8o {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.fi6zpub0i {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.549 13.755c.7 0 1.29.482 1.45 1.134a.294.294 0 0 1-.286.365h-2.39a.247.247 0 0 1-.243-.291a1.5 1.5 0 0 1 1.469-1.208");
}

.fimazrbie {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.948 12.374l.002-.002l.002-.001l.004-.004l.013-.01l.039-.03q.047-.034.127-.085c.107-.067.258-.15.45-.226a3.04 3.04 0 0 1 1.599-.17a.572.572 0 1 1-.178 1.13a1.9 1.9 0 0 0-1 .103a1.6 1.6 0 0 0-.322.17l-.009.007a.572.572 0 0 1-.727-.882");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.frw02xb6z {
  d: path("m21.153 8.348l.46.228c.804.4 1.264 1.314 1.092 2.286l-.632 3.256c-.057.337-.28.563-.613.572h-.02s.058-.971.115-1.543c.047-.464-.034-.605-.46-1.028c-.23-.229-.402-.572-.402-.914v-.915c0-.285-.23-.514-.46-.571c-.689-.171-2.125-.457-4.194-.457s-3.505.286-4.195.457a.56.56 0 0 0-.46.571v.915c0 .342-.115.685-.402.914l-.172.171c-.23.172-.345.514-.345.8c.057.629.115 1.543.115 1.543q-.027 0-.053-.002a.68.68 0 0 1-.637-.57l-.632-3.256c-.115-.915.345-1.829 1.15-2.229l.46-.228c.287-.172.574-.4.861-.629l1.035-1.085c.632-.572 1.551-.743 2.356-.343a3.15 3.15 0 0 0 1.78 0c.863-.286 1.84-.057 2.53.571l.861.857c.23.286.517.457.862.629");
}

.ft5dv1b6b {
  fill: none;
}

.fve8fmbgh {
  stop-color: var(--svg-color--4f3733, #4F3733);
}

.fwajr3bwa {
  stop-color: var(--svg-color--503833, #503833);
  stop-opacity: 0;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.gabhccily {
  stop-color: var(--svg-color--544442, #544442);
  stop-opacity: 0;
}

.gb3ua4f-n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.134 10.133v.961c-.008.16-.075.515-.276.666");
}

.gevp4whvm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.256 14.248c.068.091-.074.202-.236.323c-.162.12-.282.206-.35.115s.008-.263.17-.384c.162-.12.348-.145.416-.054");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.grjy2ibxl {
  cx: 10.904px;
  cy: 15.287px;
  r: 1.788px;
}

.gwwxrtb_v {
  stop-color: var(--svg-color--1d5894, #1D5894);
}

.h2thr5bul {
  stop-color: var(--svg-color--281414, #281414);
  stop-opacity: 0;
}

.h6orixb7r {
  stop-color: var(--svg-color--5a4745, #5A4745);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
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

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.id0lipbed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.idef6gfar {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.igdnfmbpz {
  stop-color: var(--svg-color--5a4947, #5A4947);
  stop-opacity: 0;
}

.ikjh3ionc {
  d: path("m20.237 9.262l-3.297 1.1a1.122 1.122 0 0 0 .503 2.175l3.278-.439z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j92tbybrc {
  cx: 13.36px;
  cy: 14.454px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.417px;
  ry: 0.211px;
}

.jia0zn94s {
  stop-color: var(--svg-color--544442, #544442);
}

.jqrkc7szc {
  stop-color: var(--svg-color--2a191d, #2A191D);
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kgldmvbwx {
  d: path("m15.581 14.982l-.57 1.82a.578.578 0 0 0 .559.75h.842a.58.58 0 0 0 .557-.75l-.569-1.82c-.122-.404-.691-.404-.819 0");
}

.kwqh1abfs {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.581 14.982l-.57 1.82a.578.578 0 0 0 .559.75h.842a.58.58 0 0 0 .557-.75l-.569-1.82c-.122-.404-.691-.404-.819 0");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc0lwfbjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
}

.lckvribwd {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.696 15.157l-.88 1.82c-.108.375.153.75.524.75h.79c.37 0 .631-.381.522-.75l-.533-1.82c-.115-.404-.303-.404-.423 0");
}

.lcts4tbut {
  fill: var(--svg-color--000, #000);
  d: path("M17.78 15.001c0-.304.243-.547.547-.547a.545.545 0 0 1 .486.8h-.968a.5.5 0 0 1-.066-.253");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
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

.lq2g98b5s {
  stop-color: var(--svg-color--281414, #281414);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m16jdvb1f {
  stop-color: var(--svg-color--685755, #685755);
  stop-opacity: 0;
}

.m8b0uf44i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.77 12.219c.46-.081 1.359-.058 1.98.426");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcuv6-nuk {
  stop-color: var(--svg-color--4298d4, #4298D4);
  stop-opacity: 0;
}

.mdbc_mbcb {
  stroke: var(--svg-color--4c3332, #4C3332);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mtfxop-pk {
  stop-color: var(--svg-color--43bbff, #43BBFF);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n4l_fgb1u {
  cx: 13.36px;
  cy: 14.454px;
  rx: 0.417px;
  ry: 0.211px;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nnha85vdf {
  stop-color: var(--svg-color--251014, #251014);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oz8qvprqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.pa_nigs1j {
  stop-color: var(--svg-color--5a4947, #5A4947);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psmqb459k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.064 3.03c.68-.344 2.468-.57 3.187-.524");
}

.q32ba3wcl {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.975 12.374l-.001-.002l-.002-.001l-.005-.004l-.013-.01a2 2 0 0 0-.166-.115a3 3 0 0 0-.45-.226a3.04 3.04 0 0 0-1.598-.17a.572.572 0 1 0 .178 1.13c.426-.068.768.011 1 .103a1.6 1.6 0 0 1 .322.17l.009.007a.572.572 0 0 0 .726-.883");
}

.q4q53m76f {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
  stop-opacity: 0;
}

.q920b5bgt {
  stop-color: var(--svg-color--2691ff, #2691FF);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qe_-3ab1e {
  stop-color: var(--svg-color--499efa, #499EFA);
}

.qg9x9catg {
  stop-color: var(--svg-color--503833, #503833);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r-iyesm5a {
  d: path("M14.521 14.889c0-.309-.25-.514-.319-.577l-.308.299l.19.386z");
}

.r0adxvbzx {
  stop-color: var(--svg-color--54acf3, #54ACF3);
  stop-opacity: 0;
}

.r7flkhbpm {
  stop-color: var(--svg-color--419ae2, #419AE2);
  stop-opacity: 0;
}

.rjn5j4bgi {
  stop-color: var(--svg-color--30171b, #30171B);
  stop-opacity: 0;
}

.rl4irpj3j {
  d: path("M7.788 26.79L2.344 16.695l4.594-.812l4.038 7.877c-1.35 2.025-2.688 2.865-3.188 3.032");
}

.rpjijqwhi {
  stop-color: var(--svg-color--2882ff, #2882FF);
  stop-opacity: 0;
}

.ryjfaggzx {
  fill: var(--svg-color--000, #000);
  d: path("M14.196 15.001a.545.545 0 0 0-.548-.547a.545.545 0 0 0-.486.8h.968a.54.54 0 0 0 .065-.253");
}

.s3qs9xb1s {
  stop-color: var(--svg-color--5a4745, #5A4745);
  stop-opacity: 0;
}

.s68j-sb_c {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.s9v__5azz {
  stop-color: var(--svg-color--2d1717, #2D1717);
  stop-opacity: 0;
}

.sg9fyvxai {
  stop-color: var(--svg-color--54acf3, #54ACF3);
}

.sjcrub2lh {
  stop-color: var(--svg-color--4c3232, #4C3232);
}

.snh9c8fxs {
  stop-color: var(--svg-color--2d1716, #2D1716);
  stop-opacity: 0;
}

.ssq48xbfd {
  stop-color: var(--svg-color--1d5894, #1D5894);
  stop-opacity: 0;
}

.sv-2dkb_f {
  d: path("M18.327 14.046a.956.956 0 0 1 .921 1.208h-1.846a.96.96 0 0 1 .925-1.208");
}

.t_qwphcjx {
  stop-color: var(--svg-color--2a99ff, #2A99FF);
}

.t4nmlm7ht {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
}

.ttw1-g7zn {
  stop-color: var(--svg-color--251014, #251014);
}

.tuzqszfby {
  stop-color: var(--svg-color--3a95fa, #3A95FA);
}

.ubeq2y34d {
  stop-color: var(--svg-color--419ae2, #419AE2);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ucmtgi-2a {
  stop-color: var(--svg-color--49abff, #49ABFF);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uj4h67pks {
  d: path("M13.649 14.046a.956.956 0 0 0-.922 1.208h1.847a1 1 0 0 0 .035-.252a.963.963 0 0 0-.96-.956");
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uq-5i0dud {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.427 13.755c-.7 0-1.29.482-1.451 1.134a.294.294 0 0 0 .287.365h2.39a.247.247 0 0 0 .243-.291a1.5 1.5 0 0 0-1.469-1.208");
}

.v99wjxblu {
  stop-color: var(--svg-color--63504e, #63504E);
}

.veix-z38b {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.155 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.vg834-1ys {
  d: path("M19.178 14.875a.9.9 0 0 0-.248-.495l-.278.305l.126.245z");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vsxiggb-z {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.53 18.244a.214.214 0 0 0-.255.044a.2.2 0 0 0-.022.253a2.08 2.08 0 0 0 1.738.928c.729 0 1.37-.372 1.737-.929a.2.2 0 0 0-.022-.254a.214.214 0 0 0-.254-.042c-.423.22-.92.346-1.461.346a3.2 3.2 0 0 1-1.461-.346Z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wfxtb3qbv {
  stop-color: var(--svg-color--4e4240, #4E4240);
}

.wgkuwteff {
  stop-color: var(--svg-color--4b3330, #4B3330);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wkrt2mblo {
  stop-color: var(--svg-color--1284d5, #1284D5);
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x034jqb5d {
  stop-color: var(--svg-color--2882ff, #2882FF);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xli568bjl {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
}

.xr5reebcs {
  stop-color: var(--svg-color--4bb4ff, #4BB4FF);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y-9i83_gz {
  stop-color: var(--svg-color--2d1716, #2D1716);
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ygsync4_o {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.155-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.yzvp5u7xf {
  stop-color: var(--svg-color--513d3d, #513D3D);
}

.z9wcvylbn {
  stop-color: var(--svg-color--347bc6, #347BC6);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zbtcl2bba {
  d: path("M18.256 14.248c.068.091-.074.202-.236.323c-.162.12-.282.206-.35.115s.008-.263.17-.384c.162-.12.348-.145.416-.054");
}

.zi5l5kj0o {
  stop-color: var(--svg-color--4298d4, #4298D4);
}

.zoki_jbgf {
  d: path("m10.527 14.631l.053.002s-.058-.914-.115-1.543c0-.286.115-.628.345-.8l.172-.171c.287-.229.402-.572.402-.914v-.915c0-.285.173-.514.46-.57c.69-.172 2.126-.458 4.195-.458s3.505.286 4.195.457c.23.057.46.286.46.571v.915c0 .342.172.685.402.914c.537.377.504.584.46 1.028c-.058.572-.116 1.543-.116 1.543h.02l-.285 4.24c-.172 1.896-1.662 3.217-3.44 3.217h-3.439c-1.834 0-3.267-1.321-3.439-3.217z");
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
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
