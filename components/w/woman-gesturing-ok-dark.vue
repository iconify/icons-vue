<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLEWTEe)"><path fill="url(#i5vI1Ug)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#imziqvc)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#isGoDDc)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#im41aWb)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#i68DYJb)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#iHCT2sd)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#iR33Gxc)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#iai0Slc)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#idsg4vc)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#iIpnbHc)" clip-rule="evenodd" class="eu0_hkk2v"/><path fill="url(#ite6rtb)" clip-rule="evenodd" class="eu0_hkk2v"/></g><rect fill="url(#ic0IBDd)" class="dxzw93b7u"/><rect fill="url(#iMfcj3d)" class="dxzw93b7u"/><g filter="url(#i44A9Qb)"><path fill="url(#igSvB4J)" class="yzi21fb4g"/><path fill="url(#ispaMAc)" class="yzi21fb4g"/><path fill="url(#ilxYs3d)" class="yzi21fb4g"/><path fill="url(#ie0DMEq)" class="yzi21fb4g"/><path fill="url(#ihH6Xgq)" class="yzi21fb4g"/><path fill="url(#i7lYZAD)" class="yzi21fb4g"/><path fill="url(#if1SLsb)" class="yzi21fb4g"/><path fill="url(#in5Yvad)" class="yzi21fb4g"/><path fill="url(#i33AIMd)" class="yzi21fb4g"/></g><path fill="url(#iyxuAGd)" class="ggskh2bzm"/><path fill="url(#iTFLztb)" class="ggskh2bzm"/><path fill="url(#iRnp8Ge)" class="dw85flb0t"/><path fill="url(#i4oYYjb)" class="dw85flb0t"/><path fill="url(#iHW23Gc)" class="xg-84-b0v"/><path fill="url(#iUaTakc)" class="xg-84-b0v"/><path fill="url(#iBW95Ad)" class="p49nfmexu"/><path fill="url(#icK1TWc)" class="p49nfmexu"/><g filter="url(#iTNjSLb)"><path fill="url(#i7Zcrjd)" class="lnlk8lb5t"/></g><g filter="url(#iAFym4b)"><path stroke="url(#iRYaePc)" class="yk5l_u5eu"/></g><path class="fd_orqb8o"/><path stroke="url(#i66AH3c)" class="djebsbcjo"/><path stroke="url(#ieShG0d)" class="djebsbcjo"/><path stroke="url(#if9JlAb)" class="w930jqbym"/><path stroke="url(#ikDe6mb)" class="w930jqbym"/><path stroke="url(#ieO98ab)" class="w930jqbym"/><path stroke="url(#iMRszjb)" class="w930jqbym"/><path class="idef6gfar"/><path stroke="url(#iufEA5d)" class="cvtf9k6wz"/><path stroke="url(#i4Dl8Id)" class="cvtf9k6wz"/><path stroke="url(#iE2z5Zq)" class="aj6pj94ss"/><path stroke="url(#iQ1gZ8G)" class="aj6pj94ss"/><path stroke="url(#i8A8EoW)" class="aj6pj94ss"/><path stroke="url(#iyAPa1K)" class="aj6pj94ss"/><path stroke="url(#iVpEied)" class="zw6cmm23y"/><path class="pu4sxsbhu"/><path stroke="url(#i5NYVmc)" class="zw6cmm23y"/><path stroke="url(#i0C0K2d)" class="zw6cmm23y"/><path stroke="url(#i3B38ob)" class="abd3-ibar"/><path stroke="url(#iSD4mwe)" class="abd3-ibar"/><path stroke="url(#i5qddYb)" class="abd3-ibar"/><path stroke="url(#iJlii9q)" class="abd3-ibar"/><path class="s68j-sb_c"/><path stroke="url(#i9zbruc)" class="hockzyb4d"/><path stroke="url(#i3sOJ7d)" class="lgc2wbcpd"/><path stroke="url(#iQsfHle)" class="lgc2wbcpd"/><path fill="url(#idkSmhJ)" class="eim_mrbrv"/><path fill="url(#iVm4I3c)" class="eim_mrbrv"/><path fill="url(#iMQr3Cm)" class="r_9_ioa3h"/><path fill="url(#iw1Rh0J)" class="r_9_ioa3h"/><g filter="url(#ik7Vb7N)"><path stroke="url(#i6BOZ7d)" class="ngb3gwb-q"/></g><g filter="url(#ig8KeAe)"><path stroke="url(#i4Oggfy)" class="gsuhbzbgv"/></g><g filter="url(#iU6iP0c)"><path stroke="url(#i3hXg4c)" class="yztoedc1k"/></g><g filter="url(#iuOznLd)"><path stroke="url(#iXTE8Ce)" class="h-8-hirxp"/></g><g filter="url(#ibDqDXd)"><path fill="url(#i8vESRS)" class="cge-06e6d"/></g><g filter="url(#i4GgjEd)"><path fill="url(#ibhuzhc)" class="r2ks1acbs"/><path fill="url(#ipQiwKc)" class="r2ks1acbs"/></g><g filter="url(#iUxP3qe)"><path class="fgud87tlx"/><path fill="url(#i9rOROb)" class="pe0qi5mah"/></g><g filter="url(#ivai3Qd)"><path class="ahd5oubud"/><path fill="url(#iyumdeb)" class="kcb82-blj"/></g><g filter="url(#iQTbr8d)"><path fill="url(#iix4nod)" class="yusc9cezc"/><path fill="url(#impErPc)" class="yusc9cezc"/><path fill="url(#ivIEuFz)" class="yusc9cezc"/><path fill="url(#iLbfsrb)" class="yusc9cezc"/><path fill="url(#iCG8cje)" class="yusc9cezc"/><path fill="url(#i5q5hvd)" class="yusc9cezc"/><path fill="url(#igCPZcb)" class="yusc9cezc"/><path fill="url(#iKc4fGd)" class="yusc9cezc"/></g><path fill="url(#iJikJUe)" class="yusc9cezc"/><g filter="url(#i1sIxKc)"><path class="svjoxxbrm"/></g><g filter="url(#iPAgZcb)"><path class="bo5yj0bsf"/><path fill="url(#izrC6td)" class="dzisxhces"/><path fill="url(#iiX5Jmb)" class="dzisxhces"/><path fill="url(#i3jedmc)" class="dzisxhces"/><path fill="url(#iFY7gvc)" class="dzisxhces"/></g><path fill="url(#iYnOcde)" class="dzisxhces"/><path fill="url(#i40zRWf)" class="dzisxhces"/><path stroke="url(#iQVuSoh)" class="jtr56e44r"/><g filter="url(#iqtpJMe)"><path class="yydic_0nv"/></g><g filter="url(#iBA5q2b)"><path class="too-gcbwz"/></g><g filter="url(#ivx5Rue)"><path class="ei23labpq"/></g><g filter="url(#iebiLqh)"><path clip-rule="evenodd" class="txt-bfbup"/></g><path class="m33yv-bpc"/><path fill="url(#i56egCd)" class="lzcmlfbqz"/><path class="n4hix_bhp"/><g filter="url(#iHOGvqa)"><path class="teyonbjbu"/><path fill="url(#ilRlc0b)" class="kjvx32hly"/></g><g filter="url(#iS5mReM)"><path fill="url(#i7WK6Ad)" class="gjhuyfe9u"/></g><path class="xetzygbqp"/><path fill="url(#iJkHGte)" class="x9oqg-bmc"/><path class="mimx4yb6d"/><g filter="url(#ie2FJEz)"><path fill="url(#iBawDeb)" class="sytwfz9rc"/></g><g filter="url(#iXyUoYh)"><ellipse transform="rotate(-27.914 13.307 14.561)" class="j3dy_9tgu"/><ellipse fill="url(#i1aAWNe)" transform="rotate(-27.914 13.307 14.561)" class="yqu3flbgz"/></g><g filter="url(#i6mGApb)"><path class="gejjkxweg"/></g><g filter="url(#i4pTPDe)"><path class="eiazm2nnh"/></g><g filter="url(#iprf0Qc)"><path class="tvqkfx6am"/><path fill="url(#iVJKNig)" class="lq3uy36ml"/><path fill="url(#iXT5eqc)" class="lq3uy36ml"/></g><g filter="url(#in7TsIc)"><path class="n9vytubjy"/><path fill="url(#iaKpYTb)" class="v_31fl4ku"/><path fill="url(#iBpCHed)" class="v_31fl4ku"/></g><g filter="url(#i0PkSvb)"><path stroke="url(#iKOmKZD)" class="pgznzablw"/></g><g filter="url(#i6DYJSd)"><path class="oc40kybwb"/></g><defs><radialGradient id="imziqvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.66218 5.00342 -6.25028 -.8272 15.669 18.066)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="isGoDDc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.483 11.103)scale(3.8163 5.01431)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="im41aWb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.496 10.422)scale(2.36201 1.8137)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i68DYJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41643 2.31775 -1.63264 -.99774 11.18 13.339)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iHCT2sd" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 .707 13.284)scale(3.24189 4.50024)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iR33Gxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58186 1.58197 -2.21078 -2.21063 22.401 8.758)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iai0Slc" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.095 8.92)scale(2.10723 4.39447)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="idsg4vc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.673 10.521)scale(3.18537 4.05768)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iIpnbHc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.788 -1.723)scale(3.07327 2.43078)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ite6rtb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6505 .17313 -.28052 2.67428 9.26 14.347)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ic0IBDd" cx="0" cy="0" r="1" gradientTransform="matrix(2.4546 2.4656 -3.03258 3.01906 15.064 22.008)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="zu__wcbib"/><stop offset="1" class="v1cdxsyyg"/></radialGradient><radialGradient id="iMfcj3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.83127 1.3003 0 16.983 25.298)" gradientUnits="userSpaceOnUse"><stop class="qdqqfixaa"/><stop offset="1" class="yvt-nqbiu"/></radialGradient><radialGradient id="ispaMAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.23667 -6.20284 0 16 20.756)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="w58diel4g"/><stop offset="1" class="v6fmdibat"/></radialGradient><radialGradient id="ilxYs3d" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.96 8.252)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="c74g9abcg"/><stop offset=".435" class="k33dgh0kx"/></radialGradient><radialGradient id="ie0DMEq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.985 14.584)" gradientUnits="userSpaceOnUse"><stop class="yu6zwbb_v"/><stop offset=".821" class="ksxm-h6au"/></radialGradient><radialGradient id="ihH6Xgq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.772)" gradientUnits="userSpaceOnUse"><stop class="jcr-_pt7q"/><stop offset="1" class="vtkyaex6k"/></radialGradient><radialGradient id="i7lYZAD" cx="0" cy="0" r="1" gradientTransform="rotate(120.342 2.473 5.772)scale(1.39468 3.26296)" gradientUnits="userSpaceOnUse"><stop class="t_fx8fd6d"/><stop offset="1" class="u3wjuqrnp"/></radialGradient><radialGradient id="if1SLsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13764 1.26425 -3.01923 -5.10504 10.375 18.694)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="rn8u6nbre"/><stop offset="1" class="zigbbibav"/></radialGradient><radialGradient id="in5Yvad" cx="0" cy="0" r="1" gradientTransform="rotate(59.077 7.488 25.014)scale(7.31511 1.73016)" gradientUnits="userSpaceOnUse"><stop class="i01-9l3nj"/><stop offset="1" class="jyzgzgaon"/></radialGradient><radialGradient id="i33AIMd" cx="0" cy="0" r="1" gradientTransform="rotate(54.389 5.84 25.868)scale(1.53089 3.55542)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="p2il30bmc"/><stop offset="1" class="pcu2ods2z"/></radialGradient><radialGradient id="iyxuAGd" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="p96ugv3bq"/><stop offset="1" class="kaz2mfb2i"/></radialGradient><radialGradient id="iTFLztb" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="oc_nn33wh"/><stop offset="1" class="cxw9pac7i"/></radialGradient><radialGradient id="iRnp8Ge" cx="0" cy="0" r="1" gradientTransform="rotate(151.671 11.428 5.79)scale(3.23829 1.54626)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="fqnyw0bnc"/><stop offset="1" class="yysatcquz"/></radialGradient><radialGradient id="i4oYYjb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.402 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="dg25vhy-y"/><stop offset="1" class="dn15o-0do"/></radialGradient><radialGradient id="iHW23Gc" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="sjcrub2lh"/><stop offset="1" class="wgkuwteff"/></radialGradient><radialGradient id="iUaTakc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.078 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="wfxtb3qbv"/><stop offset="1" class="eax729dsn"/></radialGradient><radialGradient id="iBW95Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.389)" gradientUnits="userSpaceOnUse"><stop class="v99wjxblu"/><stop offset=".469" class="fve8fmbgh"/></radialGradient><radialGradient id="icK1TWc" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="pa_nigs1j"/><stop offset="1" class="igdnfmbpz"/></radialGradient><radialGradient id="i7Zcrjd" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.212 16.603)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="x733f4b8w"/><stop offset="1" class="doo06bbod"/></radialGradient><radialGradient id="i66AH3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2142 -2.07063 5.3651 -.555 12.766 3.92)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="ieShG0d" cx="0" cy="0" r="1" gradientTransform="matrix(2.11795 2.22809 -3.41166 3.24302 12.504 1.407)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="ieO98ab" cx="0" cy="0" r="1" gradientTransform="rotate(96.911 7.948 9.531)scale(.2597 1.09361)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iMRszjb" cx="0" cy="0" r="1" gradientTransform="matrix(.14465 -1.10153 3.9101 .51345 19.603 3.254)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="iufEA5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.91565 5.00841 0 13.953 4.157)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="snh9c8fxs"/><stop offset=".951" class="y-9i83_gz"/></radialGradient><radialGradient id="i4Dl8Id" cx="0" cy="0" r="1" gradientTransform="matrix(1.57086 2.47251 -3.5045 2.22651 13.953 2.174)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="i8A8EoW" cx="0" cy="0" r="1" gradientTransform="matrix(.03363 .53517 -1.63373 .10266 17.773 3.874)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iyAPa1K" cx="0" cy="0" r="1" gradientTransform="matrix(.05835 -1.56885 4.81421 .17906 18.499 4.089)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="iVpEied" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 -.90625 8.05091 -1.87395 13.97 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="i5NYVmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36455 4.31533 0 13.808 4.777)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="i0C0K2d" cx="0" cy="0" r="1" gradientTransform="rotate(52.458 3.489 15.695)scale(2.22121 3.36062)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="s9v__5azz"/><stop offset="1" class="bcjkesbyj"/></radialGradient><radialGradient id="i5qddYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.008 .32792 -1.41492 -.03451 17.966 4.614)" gradientUnits="userSpaceOnUse"><stop class="bbijeebsz"/><stop offset="1" class="aypdg85ht"/></radialGradient><radialGradient id="iJlii9q" cx="0" cy="0" r="1" gradientTransform="matrix(.0445 -1.1349 5.86959 .23018 18.412 4.578)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gabhccily"/><stop offset="1" class="jia0zn94s"/></radialGradient><radialGradient id="i9zbruc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06965 -1.61842 4.37527 -.1883 13.456 6.063)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="snh9c8fxs"/><stop offset="1" class="y-9i83_gz"/></radialGradient><radialGradient id="idkSmhJ" cx="0" cy="0" r="1" gradientTransform="rotate(108.623 9.676 9.169)scale(4.23839 15.1226)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="nnha85vdf"/><stop offset="1" class="ttw1-g7zn"/></radialGradient><radialGradient id="iVm4I3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.50682 -3.31996 -1.79016 22.82 2.882)" gradientUnits="userSpaceOnUse"><stop class="h6orixb7r"/><stop offset="1" class="s3qs9xb1s"/></radialGradient><radialGradient id="iMQr3Cm" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="c2b4j9bss"/><stop offset="1" class="rjn5j4bgi"/></radialGradient><radialGradient id="iw1Rh0J" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="f_gowxnlh"/><stop offset="1" class="bx7a6gbyw"/></radialGradient><radialGradient id="ibhuzhc" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 46.696 -39.264)scale(3.0006 3.66359)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="ipQiwKc" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -15.02 48.027)scale(1.65536 .468)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i9rOROb" cx="0" cy="0" r="1" gradientTransform="matrix(1.65705 -.12326 .09636 1.29535 20.82 15.445)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iyumdeb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32443 0 0 -1.04482 10.95 15.322)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iix4nod" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.952 9.466)scale(7.85975 10.5201)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="impErPc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23492 1.06538 -.74191 -1.55636 18.005 15.656)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ivIEuFz" cx="0" cy="0" r="1" gradientTransform="matrix(1.1781 -3.81486 4.84035 1.4948 13.608 22.175)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iLbfsrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.88022 7.46275 -7.50271 -.88494 16.593 14.904)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iCG8cje" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20693 -7.24552 0 15.713 15.16)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="g1cz83i8n"/><stop offset="1" class="x_vshnm5y"/></radialGradient><radialGradient id="i5q5hvd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5787 1.4873 -2.56067 -13.04821 17.987 16.631)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="igCPZcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.26293 1.54996 0 18.526 14.272)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iKc4fGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44043 1.65083 0 13.721 14.022)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iJikJUe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41055 0 0 -7.07377 21.592 15.905)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="izrC6td" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 15.125 1.593)scale(2.29826 .7083)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iFY7gvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85536 0 0 -.23913 16.598 16.935)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i40zRWf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50485 1.03313 -1.24167 -1.8086 16.414 16.282)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="i56egCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89039 -1.41626 0 18.395 14.666)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilRlc0b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.686 2.936)scale(.41515 .57157)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJkHGte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8904 -1.41627 0 13.605 14.666)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1aAWNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00849 -.54221 .65176 -.0102 13.29 14.907)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVJKNig" cx="0" cy="0" r="1" gradientTransform="matrix(1.38503 -3.02398 1.54699 .70854 9.79 12.34)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iXT5eqc" cx="0" cy="0" r="1" gradientTransform="rotate(-123.378 9.272 2.377)scale(3.18091 4.587)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="t7u3qkefj"/><stop offset="1" class="w4h8bubsi"/></radialGradient><radialGradient id="iaKpYTb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.966 9.001)scale(5.34783 8.74338)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iBpCHed" cx="0" cy="0" r="1" gradientTransform="matrix(-.23084 1.50045 -3.22813 -.49663 16.23 7.03)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iLEWTEe" width="16.732" height="17.232" x="7.759" y="5.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="i44A9Qb" width="28.403" height="24.735" x="2.048" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.25098 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="iTNjSLb" width="16.188" height="8.656" x="9.173" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".5"/></filter><filter id="iAFym4b" width="3.994" height="4.556" x="7.973" y="22.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".25"/></filter><filter id="ik7Vb7N" width="3.508" height="1.177" x="11.476" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".125"/></filter><filter id="ig8KeAe" width="4.103" height="1.115" x="11.342" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".125"/></filter><filter id="iU6iP0c" width="4.103" height="1.115" x="11.476" y="2.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".125"/></filter><filter id="iuOznLd" width="4.288" height="1.471" x="10.461" y="1.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".125"/></filter><filter id="ibDqDXd" width="3.682" height="3.532" x="9.092" y="13.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="i4GgjEd" width="3.532" height="3.782" x="19.532" y="13.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="iUxP3qe" width="3.358" height="3.358" x="19.619" y="13.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".25"/></filter><filter id="ivai3Qd" width="2.858" height="2.858" x="9.45" y="13.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".125"/></filter><filter id="iQTbr8d" width="11.184" height="12.337" x="10.408" y="9.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="i1sIxKc" width="3.06" height="3.943" x="14.292" y="14.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".25"/></filter><filter id="iPAgZcb" width="2.56" height="3.443" x="14.72" y="14.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".125"/></filter><filter id="iqtpJMe" width="3.274" height="1.411" x="17.053" y="13.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="iBA5q2b" width="3.274" height="1.411" x="11.672" y="13.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="ivx5Rue" width="2.672" height="1.178" x="11.821" y="12.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="iebiLqh" width="2.672" height="1.178" x="17.766" y="12.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/></filter><filter id="iHOGvqa" width=".844" height=".745" x="17.599" y="14.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".05"/></filter><filter id="iS5mReM" width=".939" height=".963" x="18.53" y="14.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".1"/></filter><filter id="ie2FJEz" width="1.043" height="1.103" x="13.654" y="14.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".1"/></filter><filter id="iXyUoYh" width=".982" height=".754" x="12.816" y="14.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".05"/></filter><filter id="i6mGApb" width="3.023" height="1.615" x="17.529" y="12.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".2"/></filter><filter id="i4pTPDe" width="3.023" height="1.615" x="11.546" y="12.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".2"/></filter><filter id="iprf0Qc" width="4.344" height="4.675" x="9.165" y="7.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".15"/></filter><filter id="in7TsIc" width="9.618" height="6.397" x="12.55" y="6.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3717"/><feGaussianBlur result="effect2_foregroundBlur_4002_3717" stdDeviation=".15"/></filter><filter id="i0PkSvb" width="1.198" height="2.476" x="12.527" y="7.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".1"/></filter><filter id="i6DYJSd" width="6.907" height="3.554" x="15.435" y="8.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3717" stdDeviation=".375"/></filter><linearGradient id="i5vI1Ug" x1="21.151" x2="13.682" y1="7.691" y2="21.524" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="igSvB4J" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="ny7dycfhy"/><stop offset="1" class="xhpdgtb4r"/></linearGradient><linearGradient id="iRYaePc" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="zxa4g21za"/><stop offset="1" class="py_i1i4hl"/></linearGradient><linearGradient id="if9JlAb" x1="18.218" x2="20.905" y1="2.499" y2="3.267" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="ikDe6mb" x1="16.407" x2="18.647" y1="2.657" y2="3.347" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="iE2z5Zq" x1="17.183" x2="20.001" y1="3.124" y2="3.463" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="iQ1gZ8G" x1="15.386" x2="17.749" y1="3.627" y2="3.948" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="i3B38ob" x1="17.421" x2="19.358" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="iSD4mwe" x1="16.007" x2="18.172" y1="5.134" y2="5.083" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset="1" class="h2thr5bul"/></linearGradient><linearGradient id="i3sOJ7d" x1="17.894" x2="19.781" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="qg9x9catg"/><stop offset="1" class="fwajr3bwa"/></linearGradient><linearGradient id="iQsfHle" x1="16.55" x2="18.448" y1="5.886" y2="5.719" gradientUnits="userSpaceOnUse"><stop class="lq2g98b5s"/><stop offset=".84" class="h2thr5bul"/></linearGradient><linearGradient id="i6BOZ7d" x1="14.651" x2="11.599" y1="5.259" y2="5.98" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="i4Oggfy" x1="15.006" x2="11.492" y1="4.164" y2="5.139" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="i3hXg4c" x1="15.14" x2="11.626" y1="3.178" y2="4.153" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="iXTE8Ce" x1="14.138" x2="10.763" y1="2.372" y2="3.771" gradientUnits="userSpaceOnUse"><stop class="k35cj8b6j"/><stop offset="1" class="m16jdvb1f"/></linearGradient><linearGradient id="i8vESRS" x1="9.092" x2="12.339" y1="15.417" y2="15.417" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iiX5Jmb" x1="14.97" x2="16" y1="16.782" y2="16.782" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i3jedmc" x1="16" x2="16" y1="17.659" y2="16.99" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iYnOcde" x1="16.086" x2="16.086" y1="17.631" y2="17.477" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="iQVuSoh" x1="14.832" x2="15.338" y1="19.207" y2="18.425" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i7WK6Ad" x1="19.248" x2="18.904" y1="14.725" y2="14.938" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBawDeb" x1="14.422" x2="14.077" y1="14.725" y2="14.938" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKOmKZD" x1="12.827" x2="13.425" y1="8.519" y2="9.917" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-ok-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.ahd5oubud {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M10.879 16.5a1.179 1.179 0 1 0 0-2.357a1.179 1.179 0 0 0 0 2.357");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.aj6pj94ss {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.627c-.43-.11-2.375-.477-3.255-.266");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.aypdg85ht {
  stop-color: var(--svg-color--261111, #261111);
  stop-opacity: 0;
}

.bbijeebsz {
  stop-color: var(--svg-color--261111, #261111);
}

.bcjkesbyj {
  stop-color: var(--svg-color--2d1717, #2D1717);
}

.bf57i6byh {
  stop-color: var(--svg-color--ffd843, #FFD843);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bo5yj0bsf {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.58 14.925l-.583 1.866a.592.592 0 0 0 .572.767h.862c.405 0 .69-.39.572-.767l-.583-1.866c-.125-.413-.709-.413-.84 0");
}

.bx7a6gbyw {
  stop-color: var(--svg-color--533d3d, #533D3D);
  stop-opacity: 0;
}

.c2b4j9bss {
  stop-color: var(--svg-color--30171b, #30171B);
}

.c5ffxnbso {
  stop-color: var(--svg-color--ffdd45, #FFDD45);
}

.c74g9abcg {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cge-06e6d {
  d: path("M10.858 17.088a1.766 1.766 0 1 0 0-3.532a1.766 1.766 0 0 0 0 3.531");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cvtf9k6wz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.cxw9pac7i {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
  stop-opacity: 0;
}

.dg25vhy-y {
  stop-color: var(--svg-color--584b8c, #584B8C);
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dn15o-0do {
  stop-color: var(--svg-color--584b8c, #584B8C);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.doo06bbod {
  stop-color: var(--svg-color--9179cd, #9179CD);
  stop-opacity: 0;
}

.dw85flb0t {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.156-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.dxzw93b7u {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.986px;
  rx: 2.307px;
}

.dzisxhces {
  d: path("m15.58 14.925l-.583 1.866a.592.592 0 0 0 .572.767h.862c.405 0 .69-.39.572-.767l-.583-1.866c-.125-.413-.709-.413-.84 0");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eax729dsn {
  stop-color: var(--svg-color--4e4240, #4E4240);
  stop-opacity: 0;
}

.ei23labpq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.271 13.37l-.005.003a.294.294 0 0 1-.302-.505h.002l.003-.003l.01-.006a2 2 0 0 1 .163-.084c.108-.052.262-.117.45-.177c.373-.12.895-.22 1.458-.12a.294.294 0 0 1-.103.58c-.437-.078-.857-.001-1.176.1a3 3 0 0 0-.5.212");
}

.eiazm2nnh {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.968 12.718c-.354-.086-1.234-.043-1.822.378");
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.eu0_hkk2v {
  fill-rule: evenodd;
  d: path("M23.886 16.869a3.56 3.56 0 0 0 .355-1.566c0-.513-.105-.994-.295-1.433h.006a3.5 3.5 0 0 0-.309-.563l-.002-.004a3.56 3.56 0 0 1-.577-1.943v-.011c0-2-1.622-3.62-3.621-3.62a.59.59 0 0 1-.5-.256A3.63 3.63 0 0 0 16 5.963c-1.21 0-2.288.599-2.943 1.51a.62.62 0 0 1-.5.255l-.093.001a3.62 3.62 0 0 0-3.528 3.62v.01c0 .69-.2 1.367-.577 1.944l-.003.004a3.62 3.62 0 0 0-.241 3.562a.56.56 0 0 1 0 .5a3.6 3.6 0 0 0-.356 1.543a3.527 3.527 0 0 0 3.532 3.532h9.418a3.527 3.527 0 0 0 3.532-3.532c0-.555-.133-1.077-.355-1.544a.56.56 0 0 1 0-.5M10.43 13.936h-.014l1.316 2.585c.135 3.076 1.335 0 4.267 0s4.21 3.423 4.346.348l1.246-3.51c-.059-1.365-1.049-1.461-1.246-1.461h-3.534a4.24 4.24 0 0 1-3.5-1.836a.29.29 0 0 0-.507.056l-.09.212a2.53 2.53 0 0 1-1.305 1.355l-.057.022l-.056.023c-.259.134-.867.537-.889 1.579l.011.336z");
}

.f_gowxnlh {
  stop-color: var(--svg-color--533d3d, #533D3D);
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fd_orqb8o {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.fgud87tlx {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M21.298 16.5a1.179 1.179 0 1 0 0-2.357a1.179 1.179 0 0 0 0 2.357");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fqnyw0bnc {
  stop-color: var(--svg-color--8378b6, #8378B6);
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

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1cz83i8n {
  stop-color: var(--svg-color--2a131b, #2A131B);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gabhccily {
  stop-color: var(--svg-color--544442, #544442);
  stop-opacity: 0;
}

.gejjkxweg {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.129 12.718c.354-.086 1.234-.043 1.822.378");
}

.ggskh2bzm {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.156 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.gjhuyfe9u {
  d: path("M19.27 14.993a.92.92 0 0 0-.255-.508l-.285.313l.129.25z");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsuhbzbgv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.717 4.465c.46-.173 1.847-.438 3.353-.346");
}

.h-8-hirxp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.836 3.08c.433-.236 2.032-.622 3.538-.722");
}

.h2thr5bul {
  stop-color: var(--svg-color--281414, #281414);
  stop-opacity: 0;
}

.h6orixb7r {
  stop-color: var(--svg-color--5a4745, #5A4745);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i01-9l3nj {
  stop-color: var(--svg-color--9478d2, #9478D2);
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
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

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j3dy_9tgu {
  cx: 13.307px;
  cy: 14.561px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.428px;
  ry: 0.216px;
}

.jcr-_pt7q {
  stop-color: var(--svg-color--7357b2, #7357B2);
}

.jia0zn94s {
  stop-color: var(--svg-color--544442, #544442);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jtr56e44r {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.463 18.094c.444.237.974.373 1.537.373c.57 0 1.093-.136 1.537-.373a.22.22 0 0 1 .265.045a.21.21 0 0 1 .023.268m-3.362-.313l3.32.285m-3.32-.285a.22.22 0 0 0-.265.047a.21.21 0 0 0-.023.266m.288-.313l-.246.285m3.608.027l-.042-.027m.042.027l-.042-.027m.042.027a2.17 2.17 0 0 1-3.65 0m3.608-.027a2.12 2.12 0 0 1-3.566 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.jyzgzgaon {
  stop-color: var(--svg-color--9478d2, #9478D2);
  stop-opacity: 0;
}

.k33dgh0kx {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
  stop-opacity: 0;
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.kaz2mfb2i {
  stop-color: var(--svg-color--4c4181, #4C4181);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcb82-blj {
  d: path("M10.879 16.5a1.179 1.179 0 1 0 0-2.357a1.179 1.179 0 0 0 0 2.357");
}

.kjvx32hly {
  d: path("M18.325 14.35c.07.093-.076.207-.242.33c-.166.125-.289.212-.359.119s.009-.27.174-.394c.166-.124.357-.148.427-.055");
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.ksxm-h6au {
  stop-color: var(--svg-color--65509d, #65509D);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgc2wbcpd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lnlk8lb5t {
  d: path("M23.939 27.147c-1.95-1.2-3.037-3.417-3.36-4.157c-5.175 0-9.281 1.97-10.406 6.657H24.36c0-.9-.156-1.938-.421-2.5");
}

.lq2g98b5s {
  stop-color: var(--svg-color--281414, #281414);
}

.lq3uy36ml {
  d: path("M10.437 8.75c.62-.658 1.796-.66 2.338-.561l.435 1.416c-.278-.042-.525.056-.733.258c-.492 1.383-2.183 2.146-2.967 2.355c-.163-1.638.119-2.613.927-3.468");
}

.lzcmlfbqz {
  d: path("M18.397 14.143a.98.98 0 0 1 .944 1.237h-1.892a.983.983 0 0 1 .948-1.238");
}

.m16jdvb1f {
  stop-color: var(--svg-color--685755, #685755);
  stop-opacity: 0;
}

.m33yv-bpc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.624 13.845c.717 0 1.322.494 1.487 1.161a.3.3 0 0 1-.294.374H17.37a.253.253 0 0 1-.25-.298a1.534 1.534 0 0 1 1.505-1.238");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mimx4yb6d {
  fill: var(--svg-color--000, #000);
  d: path("M14.164 15.122a.56.56 0 0 0-.56-.56a.56.56 0 0 0-.5.818h.993a.56.56 0 0 0 .067-.258");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n4hix_bhp {
  fill: var(--svg-color--000, #000);
  d: path("M17.836 15.122c0-.311.25-.56.56-.56a.56.56 0 0 1 .5.818h-.993a.5.5 0 0 1-.067-.258");
}

.n9vytubjy {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.338 6.772c-1.243-.275-2.36.965-2.488 1.425c1.154 3.89 4.075 3.678 6.958 3.357c1.726-.191 1.913.595 2.06.975c0-4.316-3.67-5.126-6.499-5.75z");
}

.ngb3gwb-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 5.561c.392-.173 1.476-.503 2.759-.41");
}

.nnha85vdf {
  stop-color: var(--svg-color--251014, #251014);
  stop-opacity: 0;
}

.ny7dycfhy {
  stop-color: var(--svg-color--7767af, #7767AF);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.oc_nn33wh {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
}

.oc40kybwb {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.64 10.733l-1.564.288a.755.755 0 1 1-.137-1.498h2.57c1.519 0 2.021 1.531 2.083 2.054a3.45 3.45 0 0 0-2.951-.844");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p2il30bmc {
  stop-color: var(--svg-color--694eab, #694EAB);
}

.p49nfmexu {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.592-.465.81-.46l.135-.196c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.p96ugv3bq {
  stop-color: var(--svg-color--6d5ea5, #6D5EA5);
}

.pa_nigs1j {
  stop-color: var(--svg-color--5a4947, #5A4947);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pcu2ods2z {
  stop-color: var(--svg-color--694eab, #694EAB);
  stop-opacity: 0;
}

.pe0qi5mah {
  d: path("M21.298 16.5a1.179 1.179 0 1 0 0-2.357a1.179 1.179 0 0 0 0 2.357");
}

.pgznzablw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.827 8.142c.026.267.258 1.27.598 1.876");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pu4sxsbhu {
  stroke: var(--svg-color--4c3332, #4C3332);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.py_i1i4hl {
  stop-color: var(--svg-color--8477ba, #8477BA);
  stop-opacity: 0;
}

.qdqqfixaa {
  stop-color: var(--svg-color--543e3e, #543E3E);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qg9x9catg {
  stop-color: var(--svg-color--503833, #503833);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r2ks1acbs {
  d: path("M21.298 17.088a1.766 1.766 0 1 0 0-3.532a1.766 1.766 0 0 0 0 3.531");
}

.rjn5j4bgi {
  stop-color: var(--svg-color--30171b, #30171B);
  stop-opacity: 0;
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rn8u6nbre {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
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

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.s9v__5azz {
  stop-color: var(--svg-color--2d1717, #2D1717);
  stop-opacity: 0;
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sjcrub2lh {
  stop-color: var(--svg-color--4c3232, #4C3232);
}

.snh9c8fxs {
  stop-color: var(--svg-color--2d1716, #2D1716);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.svjoxxbrm {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.57 15.077l-.751 1.866a.592.592 0 0 0 .571.767h.863c.405 0 .69-.39.572-.767l-.584-1.866c-.125-.413-.54-.413-.672 0");
}

.sytwfz9rc {
  d: path("M14.498 15.007c0-.316-.258-.527-.327-.591l-.317.306l.195.396z");
}

.t_fx8fd6d {
  stop-color: var(--svg-color--9179c9, #9179C9);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t7u3qkefj {
  stop-color: var(--svg-color--545253, #545253);
  stop-opacity: 0;
}

.teyonbjbu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.325 14.35c.07.093-.076.207-.242.33c-.166.125-.289.212-.359.119s.009-.27.174-.394c.166-.124.357-.148.427-.055");
}

.too-gcbwz {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.747 14.697c-.291-.512-.734-.917-1.687-.917c-.418 0-.82.116-1.178.405c-.295.238-.255.543-.027.657l.61.349c.716-.232 1.507-.263 2.282-.494");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ttw1-g7zn {
  stop-color: var(--svg-color--251014, #251014);
}

.tvqkfx6am {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.437 8.75c.62-.658 1.796-.66 2.338-.561l.435 1.416c-.278-.042-.525.056-.733.258c-.492 1.383-2.183 2.146-2.967 2.355c-.163-1.638.119-2.613.927-3.468");
}

.txt-bfbup {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m20.095 12.868l-.151.253za.295.295 0 0 1-.302.505l-.005-.003a1 1 0 0 0-.124-.064a3 3 0 0 0-.376-.148a2.5 2.5 0 0 0-1.177-.1a.294.294 0 1 1-.102-.58c.563-.1 1.085 0 1.458.12a3.6 3.6 0 0 1 .613.261l.01.006l.003.002z");
}

.u3wjuqrnp {
  stop-color: var(--svg-color--9179c9, #9179C9);
  stop-opacity: 0;
}

.v_31fl4ku {
  d: path("M15.338 6.772c-1.243-.275-2.36.965-2.488 1.425c1.154 3.89 4.075 3.678 6.958 3.357c1.726-.191 1.913.595 2.06.975c0-4.316-3.67-5.126-6.499-5.75z");
}

.v1cdxsyyg {
  stop-color: var(--svg-color--502a26, #502A26);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v6fmdibat {
  stop-color: var(--svg-color--312654, #312654);
  stop-opacity: 0;
}

.v99wjxblu {
  stop-color: var(--svg-color--63504e, #63504E);
}

.vtkyaex6k {
  stop-color: var(--svg-color--7357b2, #7357B2);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w4h8bubsi {
  stop-color: var(--svg-color--545253, #545253);
}

.w58diel4g {
  stop-color: var(--svg-color--312654, #312654);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wfxtb3qbv {
  stop-color: var(--svg-color--4e4240, #4E4240);
}

.wgkuwteff {
  stop-color: var(--svg-color--4b3330, #4B3330);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x_vshnm5y {
  stop-color: var(--svg-color--2a131b, #2A131B);
}

.x733f4b8w {
  stop-color: var(--svg-color--9179cd, #9179CD);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x9oqg-bmc {
  d: path("M13.603 14.143a.98.98 0 0 0-.944 1.237h1.892q.035-.125.036-.258a.986.986 0 0 0-.984-.98");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xetzygbqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.376 13.845c-.717 0-1.322.494-1.487 1.161a.3.3 0 0 0 .294.374h2.448c.156 0 .28-.142.25-.298a1.54 1.54 0 0 0-1.505-1.238");
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xg-84-b0v {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.495-.371-.713-.366l-.233-.29c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.xhpdgtb4r {
  stop-color: var(--svg-color--5e4998, #5E4998);
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y-9i83_gz {
  stop-color: var(--svg-color--2d1716, #2D1716);
}

.yk5l_u5eu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.yqu3flbgz {
  cx: 13.307px;
  cy: 14.561px;
  rx: 0.428px;
  ry: 0.216px;
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yu6zwbb_v {
  stop-color: var(--svg-color--65509d, #65509D);
}

.yusc9cezc {
  d: path("M10.417 13.936h.014l-.012-.291l-.011-.336c.023-1.042.63-1.445.889-1.58q.026-.008.056-.021l.057-.023a2.53 2.53 0 0 0 1.305-1.355l.09-.213a.29.29 0 0 1 .507-.056a4.24 4.24 0 0 0 3.5 1.837h3.534c.197 0 1.187.096 1.246 1.462l-.13 3.373c-.136 3.075-2.537 5.14-5.47 5.14c-2.931 0-5.333-2.065-5.468-5.14z");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yvt-nqbiu {
  stop-color: var(--svg-color--543e3e, #543E3E);
  stop-opacity: 0;
}

.yydic_0nv {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.254 14.697c.29-.512.733-.917 1.687-.917c.417 0 .82.116 1.177.405c.295.238.256.543.027.657l-.61.349c-.715-.232-1.507-.263-2.282-.494");
}

.yysatcquz {
  stop-color: var(--svg-color--3d2f68, #3D2F68);
}

.yzi21fb4g {
  d: path("M6.367 5.28c.269-.07.742.028.945.085L10.5 7.53c.352.415.19.967.055 1.18L8.48 12.221a4.5 4.5 0 0 0-.11 4.382l2.96 5.634a.37.37 0 0 0 .492.152c.115-.057.365-.207.653-.378c.419-.25.916-.547 1.194-.677v.93a2.307 2.307 0 1 0 4.614 0v-.888c.368.187.864.457 1.264.674c.289.158.527.287.63.338a.37.37 0 0 0 .493-.151l2.96-5.634a4.5 4.5 0 0 0-.11-4.382l-2.075-3.512c-.135-.213-.297-.765.055-1.18l3.188-2.164c.203-.057.676-.154.945-.086c.336.086.594.329.812.688c.175.287 1.47 2.48 2.094 3.539c.563.823 1.625 3.088 1.375 5.563c-.1 1.662-.781 3.338-1.11 3.968l-4.132 7.855c-.173.33-.187.719-.08 1.076c.158.529.322 1.28.322 2.022H7.086c0-.743.164-1.493.322-2.022a1.43 1.43 0 0 0-.08-1.076l-4.133-7.855c-.328-.63-1.01-2.306-1.11-3.968c-.25-2.476.813-4.74 1.376-5.563a958 958 0 0 1 2.094-3.54c.218-.358.476-.6.812-.687");
}

.yztoedc1k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 3.48c.46-.174 1.848-.439 3.354-.347");
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zigbbibav {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
  stop-opacity: 0;
}

.zu__wcbib {
  stop-color: var(--svg-color--2c1214, #2C1214);
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.zxa4g21za {
  stop-color: var(--svg-color--8477ba, #8477BA);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
