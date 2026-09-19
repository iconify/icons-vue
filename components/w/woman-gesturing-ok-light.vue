<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i17eQmd)"><path fill="url(#iv8tOnc)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#ioyXJoA)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iXXdUAb)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#ilInUGc)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#itFsNBb)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iGz0Rne)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iFXlsPe)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iek4Kud)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iITcRUd)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#igMm1mc)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iwAGRMe)" clip-rule="evenodd" class="igkey_4nq"/><path fill="url(#iQtWO5b)" clip-rule="evenodd" class="igkey_4nq"/></g><rect fill="url(#iIqZIee)" class="iuxb-78iw"/><g filter="url(#ir555JK)"><path fill="url(#igSvB4J)" class="yzi21fb4g"/><path fill="url(#ispaMAc)" class="yzi21fb4g"/><path fill="url(#ilxYs3d)" class="yzi21fb4g"/><path fill="url(#ie0DMEq)" class="yzi21fb4g"/><path fill="url(#ihH6Xgq)" class="yzi21fb4g"/><path fill="url(#i7lYZAD)" class="yzi21fb4g"/><path fill="url(#if1SLsb)" class="yzi21fb4g"/><path fill="url(#in5Yvad)" class="yzi21fb4g"/><path fill="url(#i33AIMd)" class="yzi21fb4g"/></g><path fill="url(#iQa1PAb)" class="c8ibr1bzw"/><path fill="url(#iCDIMGb)" class="c8ibr1bzw"/><path fill="url(#iRnp8Ge)" class="ygsync4_o"/><path fill="url(#iZdzdac)" class="ygsync4_o"/><path fill="url(#i9ATG8d)" class="xg-84-b0v"/><path fill="url(#ijFyBlc)" class="xg-84-b0v"/><path fill="url(#izG65ob)" class="p49nfmexu"/><path fill="url(#iqfRMNF)" class="p49nfmexu"/><g filter="url(#iCti1wJ)"><path fill="url(#i7Zcrjd)" class="lnlk8lb5t"/></g><g filter="url(#iThPSac)"><path stroke="url(#iRYaePc)" class="yk5l_u5eu"/></g><path stroke="url(#i7AyVUc)" class="djebsbcjo"/><path stroke="url(#i3fcDvw)" class="djebsbcjo"/><path stroke="url(#iMCL7Ep)" class="djebsbcjo"/><path class="zoy4bqbmr"/><path stroke="url(#ifXGk1d)" class="w930jqbym"/><path stroke="url(#iGBGCYb)" class="w930jqbym"/><path stroke="url(#ipfeOLc)" class="cvtf9k6wz"/><path stroke="url(#i1auEWd)" class="cvtf9k6wz"/><path stroke="url(#iJgax7d)" class="cvtf9k6wz"/><path class="e7_20qe3q"/><path stroke="url(#iWfv0ad)" class="aj6pj94ss"/><path stroke="url(#ixlsU5P)" class="aj6pj94ss"/><path stroke="url(#iaB4TJb)" class="zw6cmm23y"/><path stroke="url(#ifw7fHd)" class="zw6cmm23y"/><path stroke="url(#irxoBpb)" class="zw6cmm23y"/><path class="jh3kajxvi"/><path stroke="url(#i5FFNib)" class="abd3-ibar"/><path stroke="url(#iIu8Rhd)" class="abd3-ibar"/><path stroke="url(#iRHom1b)" class="hockzyb4d"/><path stroke="url(#i8nLFcd)" class="hockzyb4d"/><path stroke="url(#iU90igb)" class="hockzyb4d"/><path class="pwg4g4b6s"/><path stroke="url(#iDQOVwm)" class="lgc2wbcpd"/><path stroke="url(#iIpvJFe)" class="lgc2wbcpd"/><path fill="url(#iLjyNhd)" class="eim_mrbrv"/><path fill="url(#ixYC5Kd)" class="r_9_ioa3h"/><path fill="url(#iSyDdEe)" class="r_9_ioa3h"/><g filter="url(#iD1PcId)"><path stroke="url(#idJfbpc)" class="ks3_kibat"/></g><g filter="url(#ivLIJcc)"><path stroke="url(#ihcjPHb)" class="gsuhbzbgv"/></g><g filter="url(#ixBnvfd)"><path stroke="url(#i29P4Xd)" class="yztoedc1k"/></g><g filter="url(#iMd7r1b)"><path stroke="url(#iy0EQBd)" class="h-8-hirxp"/></g><g filter="url(#iXm4Nab)"><path fill="url(#igXbzxd)" class="zg0sy8i9j"/></g><g filter="url(#itAfZce)"><path fill="url(#iasAAQE)" class="w0x29v5tu"/><path fill="url(#iBuzKac)" class="w0x29v5tu"/></g><g filter="url(#iX0Eo7d)"><path class="m2jegrefa"/><path fill="url(#i3D5iSb)" class="dj-25sblg"/></g><g filter="url(#iPwy6Ie)"><path class="z8_u-btqh"/><path fill="url(#iXY0kCT)" class="ord2sz7qh"/></g><g filter="url(#iy8wtab)"><path fill="url(#i3Smvmb)" class="pi3x66bnr"/><path fill="url(#iSpznCb)" class="pi3x66bnr"/><path fill="url(#iwjCFSb)" class="pi3x66bnr"/><path fill="url(#iWn67Nd)" class="pi3x66bnr"/><path fill="url(#icxKZcd)" class="pi3x66bnr"/><path fill="url(#ijJV34c)" class="pi3x66bnr"/><path fill="url(#iaxPfod)" class="pi3x66bnr"/></g><path fill="url(#i4Q7d3D)" class="pi3x66bnr"/><g filter="url(#ilqKjGb)"><path class="u5enhgb6q"/></g><g filter="url(#i7EZ0Wb)"><path class="s0-kt_b-s"/><path fill="url(#ikQK5Ce)" class="u5gldqbne"/><path fill="url(#iodwi3d)" class="u5gldqbne"/><path fill="url(#iiOXwTc)" class="u5gldqbne"/><path fill="url(#i6qq9Le)" class="u5gldqbne"/></g><path fill="url(#insFmce)" class="u5gldqbne"/><path fill="url(#i8f09ce)" class="u5gldqbne"/><path stroke="url(#i3NDVHb)" class="n-418vbmf"/><g filter="url(#ikVf0Vd)"><path class="fh38qc-2a"/></g><g filter="url(#i5weh8c)"><path class="jb2212bio"/></g><g filter="url(#i1MriGd)"><path class="a2sd7ebfb"/></g><g filter="url(#i8NfRId)"><path clip-rule="evenodd" class="enf157ntu"/></g><path class="j8f02rbem"/><path fill="url(#iDs8lJc)" class="im7eqpb-r"/><path class="q9xjrkb4o"/><g filter="url(#i6EKK0c)"><path class="snrxdxbej"/><path fill="url(#i959kNc)" class="k6jtsu9-h"/></g><g filter="url(#iKhr6ve)"><path fill="url(#iPNF6pc)" class="e2x-hqnfw"/></g><path class="a2ne68b1u"/><path fill="url(#iTvdqld)" class="kseyrabmo"/><path class="v0g914ybc"/><g filter="url(#ikrveZI)"><path fill="url(#iKZkyac)" class="v04y6cg9g"/></g><g filter="url(#iB53CQt)"><ellipse transform="rotate(-27.914 13.367 14.592)" class="x9pvd0bro"/><ellipse fill="url(#iK36orb)" transform="rotate(-27.914 13.367 14.592)" class="zz390jdel"/></g><g filter="url(#ieHVQ6c)"><path class="x5kgb7brq"/></g><g filter="url(#i69Ooyc)"><path class="n6ouqzbjt"/></g><g filter="url(#ioTfugb)"><path class="s_aw7zbcb"/><path fill="url(#igaAg5c)" class="zw6omebjz"/></g><g filter="url(#i4E7Y5b)"><path class="drdqp-i-c"/><path fill="url(#irPIlpe)" class="c0kru943a"/><path fill="url(#iHhJUDL)" class="c0kru943a"/></g><g filter="url(#ib4V25d)"><path stroke="url(#ipRyRad)" class="bcyhs_bht"/></g><g filter="url(#iVzwZ8c)"><path class="g555xbcjd"/></g><defs><radialGradient id="ioyXJoA" cx="0" cy="0" r="1" gradientTransform="matrix(-.66586 5.03095 -6.28467 -.83179 15.741 18.116)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iXXdUAb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.503 11.137)scale(3.8373 5.04191)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ilInUGc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.51 10.451)scale(2.37501 1.82368)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="itFsNBb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.867 9.83)scale(2.73123 1.92391)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iGz0Rne" cx="0" cy="0" r="1" gradientTransform="matrix(1.51668 2.8854 -4.00537 2.10539 12.19 6.463)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iFXlsPe" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.442 9.04)scale(2.24948 3.14361)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iek4Kud" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03448 .59188 -1.23432 -4.24276 24.36 14.417)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iITcRUd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.728 10.553)scale(3.20289 4.08001)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="igMm1mc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.844 -1.752)scale(3.09018 2.44415)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iwAGRMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.65957 .17408 -.28206 2.689 9.297 14.377)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iQtWO5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45669 -1.68541 0 9.473 11.068)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="lfn4i7-tt"/><stop offset="1" class="n3-l_jn9x"/></radialGradient><radialGradient id="iIqZIee" cx="0" cy="0" r="1" gradientTransform="matrix(3.53125 2.9587 -4.23763 5.05766 14.397 21.613)" gradientUnits="userSpaceOnUse"><stop class="wofrl9bbv"/><stop offset="1" class="zt6tonx2n"/></radialGradient><radialGradient id="ispaMAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.23667 -6.20284 0 16 20.756)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="w58diel4g"/><stop offset="1" class="v6fmdibat"/></radialGradient><radialGradient id="ilxYs3d" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.96 8.252)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="c74g9abcg"/><stop offset=".435" class="k33dgh0kx"/></radialGradient><radialGradient id="ie0DMEq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.985 14.584)" gradientUnits="userSpaceOnUse"><stop class="yu6zwbb_v"/><stop offset=".821" class="ksxm-h6au"/></radialGradient><radialGradient id="ihH6Xgq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.772)" gradientUnits="userSpaceOnUse"><stop class="jcr-_pt7q"/><stop offset="1" class="vtkyaex6k"/></radialGradient><radialGradient id="i7lYZAD" cx="0" cy="0" r="1" gradientTransform="rotate(120.342 2.473 5.772)scale(1.39468 3.26296)" gradientUnits="userSpaceOnUse"><stop class="t_fx8fd6d"/><stop offset="1" class="u3wjuqrnp"/></radialGradient><radialGradient id="if1SLsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13764 1.26425 -3.01923 -5.10504 10.375 18.694)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="rn8u6nbre"/><stop offset="1" class="zigbbibav"/></radialGradient><radialGradient id="in5Yvad" cx="0" cy="0" r="1" gradientTransform="rotate(59.077 7.488 25.014)scale(7.31511 1.73016)" gradientUnits="userSpaceOnUse"><stop class="i01-9l3nj"/><stop offset="1" class="jyzgzgaon"/></radialGradient><radialGradient id="i33AIMd" cx="0" cy="0" r="1" gradientTransform="rotate(54.389 5.84 25.868)scale(1.53089 3.55542)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="p2il30bmc"/><stop offset="1" class="pcu2ods2z"/></radialGradient><radialGradient id="iQa1PAb" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.958 5.714)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="p96ugv3bq"/><stop offset="1" class="kaz2mfb2i"/></radialGradient><radialGradient id="iCDIMGb" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 3.114 5.911)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="oc_nn33wh"/><stop offset="1" class="cxw9pac7i"/></radialGradient><radialGradient id="iRnp8Ge" cx="0" cy="0" r="1" gradientTransform="rotate(151.671 11.428 5.79)scale(3.23829 1.54626)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="fqnyw0bnc"/><stop offset="1" class="yysatcquz"/></radialGradient><radialGradient id="iZdzdac" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.401 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="dg25vhy-y"/><stop offset="1" class="dn15o-0do"/></radialGradient><radialGradient id="i9ATG8d" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="xrgskrbeu"/><stop offset="1" class="youzx1gsf"/></radialGradient><radialGradient id="ijFyBlc" cx="0" cy="0" r="1" gradientTransform="matrix(.74502 .76747 -3.62255 3.5166 8.584 3.413)" gradientUnits="userSpaceOnUse"><stop class="i0xt980of"/><stop offset="1" class="n1psrewes"/></radialGradient><radialGradient id="izG65ob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.46 5.257)" gradientUnits="userSpaceOnUse"><stop class="vkm05yehh"/><stop offset=".759" class="mzksnyx6l"/></radialGradient><radialGradient id="iqfRMNF" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="uph7y6b-c"/><stop offset="1" class="ufznmm6ku"/></radialGradient><radialGradient id="i7Zcrjd" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.212 16.603)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="x733f4b8w"/><stop offset="1" class="doo06bbod"/></radialGradient><radialGradient id="i3fcDvw" cx="0" cy="0" r="1" gradientTransform="matrix(-.15093 -1.2516 6.27758 -.757 12.904 3.221)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iMCL7Ep" cx="0" cy="0" r="1" gradientTransform="rotate(55.635 5.044 11.996)scale(4.22355 4.62851)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="dx7h84bsl"/><stop offset=".896" class="e7f2o7b6i"/></radialGradient><radialGradient id="iGBGCYb" cx="0" cy="0" r="1" gradientTransform="matrix(.16688 -1.62542 5.33705 .54795 19.604 3.398)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="i1auEWd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.151 8.864 -5.072)scale(1.21254 6.13593)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iJgax7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.63304 2.73066 -3.00756 1.79864 13.653 1.855)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="ixlsU5P" cx="0" cy="0" r="1" gradientTransform="matrix(.09375 -2.125 7.91564 .34922 18.615 4.32)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="ifw7fHd" cx="0" cy="0" r="1" gradientTransform="matrix(.04203 -1.1037 3.99518 .15214 13.945 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="irxoBpb" cx="0" cy="0" r="1" gradientTransform="rotate(57.127 3.893 14.014)scale(2.59234 3.1316)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="iIu8Rhd" cx="0" cy="0" r="1" gradientTransform="matrix(.01562 -1.15625 4.63352 .06261 18.474 4.522)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="i8nLFcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05908 -1.21917 3.8426 -.1862 13.516 5.64)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="iziaq4wdz"/><stop offset="1" class="fawmdr3-g"/></radialGradient><radialGradient id="iU90igb" cx="0" cy="0" r="1" gradientTransform="rotate(85.073 5.274 8.862)scale(3.92006 3.10284)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="dx7h84bsl"/><stop offset="1" class="e7f2o7b6i"/></radialGradient><radialGradient id="iIpvJFe" cx="0" cy="0" r="1" gradientTransform="matrix(.07604 -1.3001 4.12187 .24108 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="bl2yw2f5t"/><stop offset=".915" class="vzv6bacbx"/></radialGradient><radialGradient id="iLjyNhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07831 4.16712 -14.86837 -3.84744 20.85 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="s_7ldyban"/><stop offset="1" class="wuo647bgi"/></radialGradient><radialGradient id="ixYC5Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="gt3x42bpl"/><stop offset="1" class="grtoohbub"/></radialGradient><radialGradient id="iSyDdEe" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="antc_rrkm"/><stop offset="1" class="jqq63xj1b"/></radialGradient><radialGradient id="iasAAQE" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 28.934 -15.365)scale(3.01908 3.68615)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iBuzKac" cx="0" cy="0" r="1" gradientTransform="matrix(1.45195 .81383 -.23008 .41049 21.67 13.5)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i3D5iSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.66617 -.12394 .09689 1.30248 20.92 15.48)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iXY0kCT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33172 0 0 -1.05056 10.997 15.356)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i3Smvmb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1767 3.30942 -4.42959 -9.60587 19.23 14.763)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iSpznCb" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 9.303 8.771)scale(3.8517 4.2516)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iwjCFSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4427 -4.18012 5.3038 1.83051 13.448 22.85)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iWn67Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0031 7.35974 -8.51917 -1.16114 16.67 14.936)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="pvarcdbuv"/><stop offset="1" class="nc5tcfbln"/></radialGradient><radialGradient id="icxKZcd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.6204 1.49548 -2.57476 -13.12004 18.072 16.673)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="ijJV34c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.26988 1.55848 0 18.614 14.301)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iaxPfod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44836 1.65992 0 13.783 14.05)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="i4Q7d3D" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41831 0 0 -7.11269 21.697 15.943)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ikQK5Ce" cx="0" cy="0" r="1" gradientTransform="matrix(-.5027 -2.25557 .69515 -.15492 16.94 16.745)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="i6qq9Le" cx="0" cy="0" r="1" gradientTransform="matrix(-.86007 0 0 -.24045 16.675 16.978)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="i8f09ce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51314 1.03882 -1.2485 -1.81856 16.49 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iDs8lJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89529 -1.42406 0 18.482 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i959kNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25592 -.32979 .45404 -.35234 18.23 14.79)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTvdqld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8953 -1.42406 0 13.666 14.697)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iK36orb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00854 -.5452 .65535 -.01026 13.35 14.94)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igaAg5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.39267 -3.0406 1.5555 .71246 9.83 12.357)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="irPIlpe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.33054 4.84597 -7.92287 -3.8103 18.183 6.611)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iHhJUDL" cx="0" cy="0" r="1" gradientTransform="matrix(-.2321 1.5087 -3.2459 -.49936 16.306 7.019)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="i17eQmd" width="16.823" height="17.323" x="7.788" y="5.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="ir555JK" width="28.403" height="24.735" x="2.048" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.25098 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="iCti1wJ" width="16.188" height="8.656" x="9.173" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".5"/></filter><filter id="iThPSac" width="3.994" height="4.556" x="7.973" y="22.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".25"/></filter><filter id="iD1PcId" width="3.508" height="1.177" x="11.476" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".125"/></filter><filter id="ivLIJcc" width="4.103" height="1.115" x="11.342" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".125"/></filter><filter id="ixBnvfd" width="4.103" height="1.115" x="11.476" y="2.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".125"/></filter><filter id="iMd7r1b" width="4.288" height="1.471" x="10.461" y="1.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".125"/></filter><filter id="iXm4Nab" width="3.701" height="3.551" x="9.128" y="13.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="itAfZce" width="3.551" height="3.801" x="19.625" y="13.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="iX0Eo7d" width="3.371" height="3.371" x="19.716" y="13.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".25"/></filter><filter id="iPwy6Ie" width="3.171" height="3.171" x="9.34" y="13.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".2"/></filter><filter id="iy8wtab" width="11.246" height="12.403" x="10.451" y="9.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="ilqKjGb" width="3.072" height="3.959" x="14.359" y="14.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".25"/></filter><filter id="i7EZ0Wb" width="2.572" height="3.459" x="14.789" y="14.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".125"/></filter><filter id="ikVf0Vd" width="3.291" height="1.418" x="17.135" y="13.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="i5weh8c" width="3.291" height="1.418" x="11.723" y="13.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="i1MriGd" width="2.686" height="1.183" x="11.872" y="12.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="i8NfRId" width="2.686" height="1.183" x="17.85" y="12.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/></filter><filter id="i6EKK0c" width=".848" height=".748" x="17.682" y="14.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".05"/></filter><filter id="iKhr6ve" width=".942" height=".967" x="18.619" y="14.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".1"/></filter><filter id="ikrveZI" width="1.047" height="1.106" x="13.717" y="14.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".1"/></filter><filter id="iB53CQt" width=".987" height=".757" x="12.874" y="14.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".05"/></filter><filter id="ieHVQ6c" width="2.433" height="1.017" x="17.915" y="12.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".1"/></filter><filter id="i69Ooyc" width="2.633" height="1.217" x="11.799" y="12.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".1"/></filter><filter id="ioTfugb" width="4.565" height="4.898" x="9.204" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/><feGaussianBlur result="effect2_foregroundBlur_4002_3729" stdDeviation=".15"/></filter><filter id="i4E7Y5b" width="9.618" height="6.329" x="12.607" y="6.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3729"/><feGaussianBlur result="effect2_foregroundBlur_4002_3729" stdDeviation=".125"/></filter><filter id="ib4V25d" width="1.201" height="2.487" x="12.584" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".1"/></filter><filter id="iVzwZ8c" width="8.937" height="5.566" x="14.51" y="7.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3729" stdDeviation=".875"/></filter><linearGradient id="iv8tOnc" x1="21.253" x2="13.744" y1="7.684" y2="21.593" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="igSvB4J" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="ny7dycfhy"/><stop offset="1" class="xhpdgtb4r"/></linearGradient><linearGradient id="iRYaePc" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="zxa4g21za"/><stop offset="1" class="py_i1i4hl"/></linearGradient><linearGradient id="i7AyVUc" x1="14.261" x2="10.736" y1="2.588" y2="4.348" gradientUnits="userSpaceOnUse"><stop offset=".565" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="ifXGk1d" x1="16.576" x2="20.718" y1="2.557" y2="4.814" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".704" class="aphqukgtk"/></linearGradient><linearGradient id="ipfeOLc" x1="15.286" x2="12.235" y1="3.297" y2="4.422" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iWfv0ad" x1="15.545" x2="20.274" y1="3.462" y2="4.851" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="iaB4TJb" x1="14.956" x2="12.465" y1="4.165" y2="5.276" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="i5FFNib" x1="16.265" x2="19.174" y1="4.234" y2="5.677" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="iRHom1b" x1="14.472" x2="11.788" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="do-g6qb_k"/><stop offset="1" class="dc7v1rsdf"/></linearGradient><linearGradient id="iDQOVwm" x1="16.8" x2="20.02" y1="5.254" y2="6.073" gradientUnits="userSpaceOnUse"><stop offset=".113" class="s59e5ab9a"/><stop offset=".893" class="aphqukgtk"/></linearGradient><linearGradient id="idJfbpc" x1="14.651" x2="11.599" y1="5.259" y2="5.98" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="ihcjPHb" x1="15.121" x2="11.6" y1="4.207" y2="5.388" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="i29P4Xd" x1="15.255" x2="11.734" y1="3.221" y2="4.402" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="iy0EQBd" x1="14.436" x2="11.189" y1="2.409" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="xl-zenb2y"/><stop offset="1" class="agt7cdzvy"/></linearGradient><linearGradient id="igXbzxd" x1="9.128" x2="12.394" y1="15.452" y2="15.452" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iodwi3d" x1="15.039" x2="16.074" y1="16.825" y2="16.825" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iiOXwTc" x1="16.074" x2="16.074" y1="17.707" y2="17.034" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="insFmce" x1="16.161" x2="16.161" y1="17.678" y2="17.524" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="i3NDVHb" x1="14.9" x2="15.408" y1="19.263" y2="18.477" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iPNF6pc" x1="19.34" x2="18.994" y1="14.757" y2="14.97" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKZkyac" x1="14.487" x2="14.141" y1="14.757" y2="14.97" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipRyRad" x1="12.884" x2="13.485" y1="8.516" y2="9.922" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-ok-light" /></template>
<style>
.a2ne68b1u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.436 13.871c-.72 0-1.33.497-1.495 1.168a.303.303 0 0 0 .295.377h2.462a.254.254 0 0 0 .25-.3a1.546 1.546 0 0 0-1.512-1.245");
}

.a2sd7ebfb {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.325 13.394l-.005.003a.296.296 0 0 1-.304-.508h.002l.003-.002l.01-.007a2 2 0 0 1 .164-.084a4 4 0 0 1 .453-.179c.375-.12.9-.22 1.465-.12a.296.296 0 0 1-.102.583a2.5 2.5 0 0 0-1.183.101a3 3 0 0 0-.503.213");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.agt7cdzvy {
  stop-color: var(--svg-color--ffd9c8, #FFD9C8);
  stop-opacity: 0;
}

.aj6pj94ss {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.627c-.43-.11-2.375-.477-3.255-.266");
}

.antc_rrkm {
  stop-color: var(--svg-color--ffc3aa, #FFC3AA);
}

.aphqukgtk {
  stop-color: var(--svg-color--d3a28e, #D3A28E);
  stop-opacity: 0;
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bcyhs_bht {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.884 8.137c.025.268.259 1.277.6 1.887");
}

.bl2yw2f5t {
  stop-color: var(--svg-color--bf876a, #BF876A);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c0kru943a {
  d: path("M15.409 6.76c-1.25-.277-2.373.97-2.502 1.433c1.16 3.912 4.097 3.697 6.996 3.375c1.736-.193 1.924.598 2.072.98c0-4.34-3.69-5.154-6.535-5.782z");
}

.c74g9abcg {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
}

.c8ibr1bzw {
  d: path("m7.599 4.558l-.428.666a.24.24 0 0 0 .01.278c.898 1.156 2.373 1.802 3.283 2.087a.244.244 0 0 0 .28-.107c.151-.247.354-.584.41-.69c.068-.13-.03-.231-.087-.265L8.052 4.699l.125-.274c-.35-.106-.531.044-.578.133");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
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

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.dc7v1rsdf {
  stop-color: var(--svg-color--f4c7b0, #F4C7B0);
  stop-opacity: 0;
}

.dg25vhy-y {
  stop-color: var(--svg-color--584b8c, #584B8C);
}

.dj-25sblg {
  d: path("M21.401 16.542a1.185 1.185 0 1 0 0-2.371a1.185 1.185 0 0 0 0 2.37");
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dn15o-0do {
  stop-color: var(--svg-color--584b8c, #584B8C);
  stop-opacity: 0;
}

.do-g6qb_k {
  stop-color: var(--svg-color--f4c7b0, #F4C7B0);
}

.doo06bbod {
  stop-color: var(--svg-color--9179cd, #9179CD);
  stop-opacity: 0;
}

.drdqp-i-c {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.409 6.76c-1.25-.277-2.373.97-2.502 1.433c1.16 3.912 4.097 3.697 6.996 3.375c1.736-.193 1.924.598 2.072.98c0-4.34-3.69-5.154-6.535-5.782z");
}

.dx7h84bsl {
  stop-color: var(--svg-color--d09b80, #D09B80);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e2x-hqnfw {
  d: path("M19.362 15.026a.93.93 0 0 0-.256-.51l-.287.314l.13.252z");
}

.e7_20qe3q {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.627c-.43-.11-2.375-.477-3.255-.266");
}

.e7f2o7b6i {
  stop-color: var(--svg-color--d09b80, #D09B80);
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.enf157ntu {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m20.192 12.89l-.152.253za.296.296 0 0 1-.304.508l-.005-.003l-.024-.013l-.1-.051a3 3 0 0 0-.379-.149a2.5 2.5 0 0 0-1.183-.101a.296.296 0 0 1-.103-.583c.567-.1 1.091 0 1.466.12a3.6 3.6 0 0 1 .617.263l.01.006l.003.002z");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.fawmdr3-g {
  stop-color: var(--svg-color--d29d82, #D29D82);
}

.fh38qc-2a {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.335 14.728c.292-.515.738-.922 1.696-.922c.42 0 .824.117 1.184.407c.297.24.257.547.027.662l-.614.35c-.719-.233-1.514-.264-2.293-.497");
}

.fqnyw0bnc {
  stop-color: var(--svg-color--8378b6, #8378B6);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g555xbcjd {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.73 10.743l-1.573.289a.76.76 0 1 1-.138-1.506h2.583c1.528 0 2.033 1.54 2.095 2.066a3.47 3.47 0 0 0-2.967-.85");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.grtoohbub {
  stop-color: var(--svg-color--ce9488, #CE9488);
  stop-opacity: 0;
}

.gsuhbzbgv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.717 4.465c.46-.173 1.847-.438 3.353-.346");
}

.gt3x42bpl {
  stop-color: var(--svg-color--ce9488, #CE9488);
}

.h-8-hirxp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.836 3.08c.433-.236 2.032-.622 3.538-.722");
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

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i01-9l3nj {
  stop-color: var(--svg-color--9478d2, #9478D2);
}

.i0xt980of {
  stop-color: var(--svg-color--d9ab8f, #D9AB8F);
}

.igkey_4nq {
  fill-rule: evenodd;
  d: path("M24.003 16.912a3.6 3.6 0 0 0 .357-1.575c0-.515-.106-1-.296-1.44h.006a3.5 3.5 0 0 0-.31-.566l-.003-.004a3.6 3.6 0 0 1-.58-1.954v-.011a3.64 3.64 0 0 0-3.64-3.64a.6.6 0 0 1-.503-.258a3.65 3.65 0 0 0-2.96-1.519c-1.217 0-2.3.603-2.96 1.52a.62.62 0 0 1-.502.256l-.094.001a3.64 3.64 0 0 0-3.546 3.64v.01c0 .693-.201 1.374-.581 1.955l-.003.004a3.64 3.64 0 0 0-.243 3.58a.57.57 0 0 1 0 .503a3.6 3.6 0 0 0-.357 1.553a3.546 3.546 0 0 0 3.551 3.551h9.47a3.546 3.546 0 0 0 3.551-3.551c0-.559-.133-1.083-.357-1.553a.57.57 0 0 1 0-.502m-13.529-2.95h-.014l1.323 2.6c.136 3.093 1.343 0 4.291 0s4.234 3.442 4.37.35l1.253-3.528c-.06-1.374-1.055-1.47-1.253-1.47H16.89a4.26 4.26 0 0 1-3.519-1.847a.291.291 0 0 0-.51.057l-.09.213a2.54 2.54 0 0 1-1.369 1.385l-.057.023c-.26.135-.871.54-.894 1.587l.012.338z");
}

.im7eqpb-r {
  d: path("M18.484 14.171a.985.985 0 0 1 .95 1.244H17.53a.99.99 0 0 1 .954-1.244");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.iziaq4wdz {
  stop-color: var(--svg-color--d29d82, #D29D82);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j8f02rbem {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.713 13.871c.72 0 1.33.497 1.495 1.168a.303.303 0 0 1-.296.377H17.45a.254.254 0 0 1-.25-.3a1.54 1.54 0 0 1 1.513-1.245");
}

.jb2212bio {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.814 14.728c-.293-.515-.738-.922-1.696-.922c-.42 0-.825.117-1.184.407c-.297.24-.257.547-.027.662l.613.35c.72-.233 1.515-.264 2.294-.497");
}

.jcr-_pt7q {
  stop-color: var(--svg-color--7357b2, #7357B2);
}

.jh3kajxvi {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jqq63xj1b {
  stop-color: var(--svg-color--ffc3aa, #FFC3AA);
  stop-opacity: 0;
}

.jyzgzgaon {
  stop-color: var(--svg-color--9478d2, #9478D2);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k33dgh0kx {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
  stop-opacity: 0;
}

.k6jtsu9-h {
  d: path("M18.412 14.38c.07.093-.076.207-.243.332s-.29.213-.36.119s.007-.271.174-.396s.359-.15.429-.056");
}

.kaz2mfb2i {
  stop-color: var(--svg-color--4c4181, #4C4181);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.ks3_kibat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 5.56c.392-.172 1.476-.502 2.759-.41");
}

.kseyrabmo {
  d: path("M13.664 14.171a.985.985 0 0 0-.949 1.244h1.903q.034-.126.035-.26a.99.99 0 0 0-.989-.984");
}

.ksxm-h6au {
  stop-color: var(--svg-color--65509d, #65509D);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lfn4i7-tt {
  stop-color: var(--svg-color--514d4e, #514D4E);
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

.m2jegrefa {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M21.401 16.542a1.185 1.185 0 1 0 0-2.371a1.185 1.185 0 0 0 0 2.37");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzksnyx6l {
  stop-color: var(--svg-color--f4c7ad, #F4C7AD);
}

.n-418vbmf {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.53 18.145a3.3 3.3 0 0 0 1.544.374a3.3 3.3 0 0 0 1.545-.374h.001a.22.22 0 0 1 .266.044a.214.214 0 0 1 .023.269m-3.38-.313l3.338.286m-3.338-.286a.22.22 0 0 0-.267.047a.21.21 0 0 0-.022.266m.29-.313l-.248.286m3.627.027l-.042-.027m.042.027l-.042-.027m.042.027a2.182 2.182 0 0 1-3.67 0m3.628-.027a2.132 2.132 0 0 1-3.586 0m-.041.027l.041-.027m-.041.027l.041-.027");
}

.n1psrewes {
  stop-color: var(--svg-color--d9ab8f, #D9AB8F);
  stop-opacity: 0;
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n3-l_jn9x {
  stop-color: var(--svg-color--514d4e, #514D4E);
  stop-opacity: 0;
}

.n6ouqzbjt {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.031 12.738c-.356-.086-1.24-.043-1.832.38");
}

.nc5tcfbln {
  stop-color: var(--svg-color--b47896, #B47896);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.ny7dycfhy {
  stop-color: var(--svg-color--7767af, #7767AF);
}

.oc_nn33wh {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ord2sz7qh {
  d: path("M10.925 16.542a1.185 1.185 0 1 0 0-2.371a1.185 1.185 0 0 0 0 2.37");
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

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pcu2ods2z {
  stop-color: var(--svg-color--694eab, #694EAB);
  stop-opacity: 0;
}

.pi3x66bnr {
  d: path("M10.46 13.963h.014l-.011-.293l-.012-.338c.023-1.047.634-1.452.894-1.587l.057-.023l.057-.022a2.54 2.54 0 0 0 1.312-1.362l.09-.214a.291.291 0 0 1 .51-.057a4.26 4.26 0 0 0 3.52 1.847h3.553c.198 0 1.194.096 1.253 1.47l-.131 3.391c-.136 3.093-2.551 5.17-5.499 5.17s-5.363-2.077-5.499-5.17z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvarcdbuv {
  stop-color: var(--svg-color--b47896, #B47896);
  stop-opacity: 0;
}

.pwg4g4b6s {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.py_i1i4hl {
  stop-color: var(--svg-color--8477ba, #8477BA);
  stop-opacity: 0;
}

.q9xjrkb4o {
  fill: var(--svg-color--000, #000);
  d: path("M17.92 15.156c0-.314.251-.564.564-.564a.562.562 0 0 1 .502.823h-.998a.5.5 0 0 1-.068-.26");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
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

.rn8u6nbre {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
}

.s_7ldyban {
  stop-color: var(--svg-color--cd978c, #CD978C);
  stop-opacity: 0;
}

.s_aw7zbcb {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.48 8.748c.625-.661 1.806-.662 2.352-.563l.436 1.424c-.279-.043-.527.055-.736.259c-.495 1.39-2.196 2.157-2.984 2.367c-.164-1.646.12-2.626.932-3.487");
}

.s0-kt_b-s {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.652 14.958l-.586 1.876a.595.595 0 0 0 .574.771h.868a.597.597 0 0 0 .575-.771l-.587-1.876c-.125-.416-.712-.416-.844 0");
}

.s59e5ab9a {
  stop-color: var(--svg-color--d3a28e, #D3A28E);
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.snrxdxbej {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.412 14.38c.07.093-.076.207-.243.332s-.29.213-.36.119s.007-.271.174-.396s.359-.15.429-.056");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t_fx8fd6d {
  stop-color: var(--svg-color--9179c9, #9179C9);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u3wjuqrnp {
  stop-color: var(--svg-color--9179c9, #9179C9);
  stop-opacity: 0;
}

.u5enhgb6q {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.641 15.11l-.754 1.877a.595.595 0 0 0 .574.771h.868a.597.597 0 0 0 .575-.771l-.587-1.876c-.126-.416-.544-.416-.676 0");
}

.u5gldqbne {
  d: path("m15.652 14.958l-.586 1.876a.595.595 0 0 0 .574.771h.868a.597.597 0 0 0 .575-.771l-.587-1.876c-.125-.416-.712-.416-.844 0");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ufznmm6ku {
  stop-color: var(--svg-color--d3aa91, #D3AA91);
  stop-opacity: 0;
}

.uph7y6b-c {
  stop-color: var(--svg-color--d3aa91, #D3AA91);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v04y6cg9g {
  d: path("M14.564 15.04c0-.318-.259-.53-.329-.594l-.318.307l.196.399z");
}

.v0g914ybc {
  fill: var(--svg-color--000, #000);
  d: path("M14.228 15.156a.56.56 0 0 0-.564-.564a.562.562 0 0 0-.501.823h.998a.56.56 0 0 0 .067-.26");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6fmdibat {
  stop-color: var(--svg-color--312654, #312654);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vkm05yehh {
  stop-color: var(--svg-color--ffdabd, #FFDABD);
}

.vtkyaex6k {
  stop-color: var(--svg-color--7357b2, #7357B2);
  stop-opacity: 0;
}

.vzv6bacbx {
  stop-color: var(--svg-color--bf876a, #BF876A);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w0x29v5tu {
  d: path("M21.401 17.132a1.776 1.776 0 1 0 0-3.551a1.776 1.776 0 0 0 0 3.55");
}

.w58diel4g {
  stop-color: var(--svg-color--312654, #312654);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wofrl9bbv {
  stop-color: var(--svg-color--b37d7d, #B37D7D);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wuo647bgi {
  stop-color: var(--svg-color--a97265, #A97265);
}

.x5kgb7brq {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.215 12.738c.355-.086 1.24-.043 1.832.38");
}

.x733f4b8w {
  stop-color: var(--svg-color--9179cd, #9179CD);
}

.x9pvd0bro {
  cx: 13.367px;
  cy: 14.592px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.43px;
  ry: 0.218px;
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xg-84-b0v {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.495-.371-.713-.366l-.233-.29c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.xhpdgtb4r {
  stop-color: var(--svg-color--5e4998, #5E4998);
}

.xl-zenb2y {
  stop-color: var(--svg-color--ffd9c8, #FFD9C8);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xrgskrbeu {
  stop-color: var(--svg-color--fcc4ac, #FCC4AC);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.ygsync4_o {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.155-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.yk5l_u5eu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.youzx1gsf {
  stop-color: var(--svg-color--edc1a6, #EDC1A6);
}

.yu6zwbb_v {
  stop-color: var(--svg-color--65509d, #65509D);
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

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z8_u-btqh {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M10.925 16.542a1.185 1.185 0 1 0 0-2.371a1.185 1.185 0 0 0 0 2.37");
}

.zg0sy8i9j {
  d: path("M10.904 17.132a1.776 1.776 0 1 0 0-3.551a1.776 1.776 0 0 0 0 3.55");
}

.zigbbibav {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
  stop-opacity: 0;
}

.zoy4bqbmr {
  stroke: var(--svg-color--f5c7ad, #F5C7AD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.zt6tonx2n {
  stop-color: var(--svg-color--f6c5b6, #F6C5B6);
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.zw6omebjz {
  d: path("M10.48 8.748c.625-.661 1.806-.662 2.352-.563l.436 1.424c-.279-.043-.527.055-.736.259c-.495 1.39-2.196 2.157-2.984 2.367c-.164-1.646.12-2.626.932-3.487");
}

.zxa4g21za {
  stop-color: var(--svg-color--8477ba, #8477BA);
}

.zz390jdel {
  cx: 13.367px;
  cy: 14.592px;
  rx: 0.43px;
  ry: 0.218px;
}

</style>
