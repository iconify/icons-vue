<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iTfbFfc)"><circle fill="url(#iQfFQUc)" class="vc8lfdbhz"/></g><g filter="url(#ifBnZcb)"><circle fill="url(#i1Jq7Zr)" class="p8vg5eein"/></g><g filter="url(#iuGG3Xb)"><circle fill="url(#iwk04Sd)" class="epjcn_abj"/><circle fill="url(#iyIMQMd)" class="epjcn_abj"/></g><g filter="url(#iNnyvzc)"><circle class="z-dszxbvk"/><circle fill="url(#iNgfPex)" class="t3eho4f7s"/><circle fill="url(#iaFqoXd)" class="t3eho4f7s"/></g><g filter="url(#i1T5sIv)"><path class="xc55znb2x"/><path fill="url(#iJzNhIb)" class="rmbvi9bfw"/><path fill="url(#iuhqpWv)" class="rmbvi9bfw"/><path fill="url(#iEf78cC)" class="rmbvi9bfw"/><path fill="url(#iuMT3ke)" class="rmbvi9bfw"/></g><path fill="url(#i1ryfob)" class="f0229regj"/><path fill="url(#io8R0nc)" class="f0229regj"/><path fill="url(#iupWyyd)" class="f0229regj"/><path fill="url(#irAwi8d)" class="f0229regj"/><path fill="url(#iW1Iv5t)" class="f0229regj"/><path fill="url(#inh7lSc)" class="f0229regj"/><path fill="url(#i8JJXrd)" class="f0229regj"/><path fill="url(#imuAEBe)" class="f0229regj"/><path fill="url(#iSqBlke)" class="f0229regj"/><g filter="url(#is7bNOc)"><path fill="url(#iqPrsTK)" class="x_mri4gas"/></g><rect fill="url(#ilIh1Gd)" class="iuxb-78iw"/><path fill="url(#i2QzoZV)" class="veix-z38b"/><path fill="url(#i2vOWDd)" class="veix-z38b"/><path fill="url(#i4Z432d)" class="ygsync4_o"/><path fill="url(#ivztzoe)" class="ygsync4_o"/><path fill="url(#iIpRhId)" class="r_9_ioa3h"/><path fill="url(#iZSNaSd)" class="r_9_ioa3h"/><path fill="url(#iQspthd)" class="eim_mrbrv"/><path fill="url(#icK1TWc)" class="eim_mrbrv"/><path fill="url(#iTEM0hI)" class="eim_mrbrv"/><path stroke="url(#iZpbCjj)" class="djebsbcjo"/><path stroke="url(#ixeCvRE)" class="djebsbcjo"/><g filter="url(#i5YXg4b)"><path stroke="url(#ikKzIbc)" class="psmqb459k"/></g><path stroke="url(#iHMsvOe)" class="w930jqbym"/><path stroke="url(#i74VhCe)" class="w930jqbym"/><path stroke="url(#iiOpCsb)" class="w930jqbym"/><path stroke="url(#if2KuPc)" class="w930jqbym"/><path stroke="url(#ixfHMQd)" class="cvtf9k6wz"/><path stroke="url(#iDm3fve)" class="cvtf9k6wz"/><g filter="url(#ikVWnac)"><path stroke="url(#iiety4c)" class="bw3xffbxo"/></g><path stroke="url(#ivIgzNd)" class="lc0lwfbjp"/><path stroke="url(#is9gSbd)" class="lc0lwfbjp"/><path stroke="url(#iO6NXtb)" class="lc0lwfbjp"/><path stroke="url(#ieY1Obr)" class="lc0lwfbjp"/><path stroke="url(#i9RlSAd)" class="zw6cmm23y"/><path stroke="url(#itD4eQn)" class="zw6cmm23y"/><path stroke="url(#i868Ohe)" class="abd3-ibar"/><path stroke="url(#itADcQY)" class="abd3-ibar"/><path stroke="url(#iWCAEge)" class="abd3-ibar"/><path stroke="url(#ivH8TMc)" class="abd3-ibar"/><path stroke="url(#ioyMW7d)" class="hockzyb4d"/><path stroke="url(#iwbexkd)" class="hockzyb4d"/><g filter="url(#iRNid0p)"><path stroke="url(#i56lPRb)" class="oz8qvprqg"/></g><g filter="url(#iY0f28c)"><path stroke="url(#ik2Tg9d)" class="drig65bxb"/></g><path stroke="url(#iyRoKnb)" class="lgc2wbcpd"/><path stroke="url(#ipBDPvU)" class="lgc2wbcpd"/><path stroke="url(#iUpGVUd)" class="lgc2wbcpd"/><path stroke="url(#iVi4aOc)" class="lgc2wbcpd"/><path fill="url(#iDsBXSc)" class="eim_mrbrv"/><path fill="url(#inr4b5B)" class="eim_mrbrv"/><path fill="url(#iMqJFjc)" class="r_9_ioa3h"/><path fill="url(#iuQFhPc)" class="r_9_ioa3h"/><g filter="url(#iNUBhQd)"><path fill="url(#iOz6e2d)" class="rl4irpj3j"/></g><g filter="url(#iFCuFyc)"><path stroke="url(#ipBmWWm)" class="id0lipbed"/></g><g filter="url(#ikHiTbc)"><path fill="url(#itisSwc)" class="i3ko4-nmt"/><path fill="url(#irIAGBv)" class="i3ko4-nmt"/><path fill="url(#iBJQjLs)" class="i3ko4-nmt"/></g><path fill="url(#ioBQA6l)" class="qicxwsbbh"/><path fill="url(#iArf0Dk)" class="qicxwsbbh"/><path fill="url(#iDHB9Qd)" class="qicxwsbbh"/><path fill="url(#iBfhLYd)" class="qicxwsbbh"/><g filter="url(#ifoFIMe)"><path fill="url(#icnHI8b)" class="a4bll5b1e"/></g><g filter="url(#i6IaKoc)"><path class="ftdcf6bvq"/></g><g filter="url(#iMJrn5d)"><path class="n9q0hl2we"/><path fill="url(#iWv1LZd)" class="rmj6-abyk"/><path fill="url(#iaJr89d)" class="rmj6-abyk"/><path fill="url(#iOUAAJc)" class="rmj6-abyk"/><path fill="url(#iFkmeZd)" class="rmj6-abyk"/></g><path fill="url(#i150MTJ)" class="rmj6-abyk"/><path stroke="url(#i9ETzte)" class="i90dpqbba"/><g filter="url(#iHL2pkd)"><path class="l9sn86auz"/><path fill="url(#i9HQn0b)" class="bthexfsou"/></g><g filter="url(#iwzitFc)"><path class="k_ncg-saz"/><path fill="url(#ij4y27d)" class="d_3yv0zmg"/></g><path class="skwvwv5ha"/><path fill="url(#i47nRfb)" class="xd0wwnbpf"/><path class="h5vigtbft"/><g filter="url(#irjFete)"><path class="ok_d2qbxh"/><path fill="url(#id5bUId)" class="q4qgizelv"/></g><g filter="url(#ilJ5oxb)"><path fill="url(#iNUtjtc)" class="c4-dmkhyu"/></g><path class="bhg7_d9ul"/><path fill="url(#i7o7kwb)" class="gmv08n5fw"/><path class="l65pozi8m"/><g filter="url(#iLBBzzc)"><path fill="url(#iPX4fre)" class="pp5mahhum"/></g><g filter="url(#iscriOe)"><ellipse transform="rotate(-27.914 13.217 14.394)" class="p619n6biu"/><ellipse fill="url(#i3CofBx)" transform="rotate(-27.914 13.217 14.394)" class="bgx_gfbvd"/></g><g filter="url(#iF1ayed)"><path stroke="url(#i2PVKCb)" class="e_u84p1_m"/></g><g filter="url(#iDNClBM)"><path stroke="url(#icWkR3d)" class="outbd-bsw"/></g><g filter="url(#iqr5upd)"><path stroke="url(#i66Kgkc)" class="btsqkkecy"/></g><defs><radialGradient id="iQfFQUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90046 0 0 3.32583 8.927 15.236)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iyIMQMd" cx="0" cy="0" r="1" gradientTransform="matrix(.8953 -.65191 .74407 1.02186 21.44 14.95)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iNgfPex" cx="0" cy="0" r="1" gradientTransform="matrix(.8894 -1.63586 .95747 .52057 20.993 16.125)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iaFqoXd" cx="0" cy="0" r="1" gradientTransform="matrix(.2808 .27795 -.35832 .362 21.037 15.236)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iJzNhIb" cx="0" cy="0" r="1" gradientTransform="matrix(.86401 -3.20193 1.18737 .3204 20.582 10.789)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iuhqpWv" cx="0" cy="0" r="1" gradientTransform="matrix(4.14218 .38118 -.20496 2.22722 18.803 8.883)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iEf78cC" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.81849 -2.81633 0 15.877 5.921)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iuMT3ke" cx="0" cy="0" r="1" gradientTransform="matrix(3.32899 -2.43956 3.822 5.21543 8.893 13.305)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="io8R0nc" cx="0" cy="0" r="1" gradientTransform="matrix(8.8125 0 0 9.43494 11 29.99)" gradientUnits="userSpaceOnUse"><stop class="q920b5bgt"/><stop offset="1" class="hmv6xsb8e"/></radialGradient><radialGradient id="iupWyyd" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -8.62501 6.82131 4.1521 23.375 24.35)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="bawjzlb6r"/><stop offset="1" class="ati7d-krq"/></radialGradient><radialGradient id="irAwi8d" cx="0" cy="0" r="1" gradientTransform="matrix(3 0 0 4.4849 7.5 29.99)" gradientUnits="userSpaceOnUse"><stop class="qe_-3ab1e"/><stop offset="1" class="chsdmobsg"/></radialGradient><radialGradient id="iW1Iv5t" cx="0" cy="0" r="1" gradientTransform="matrix(.87505 5.5 -7.00176 1.11398 15.126 19.538)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gwwxrtb_v"/><stop offset="1" class="ssq48xbfd"/></radialGradient><radialGradient id="inh7lSc" cx="0" cy="0" r="1" gradientTransform="rotate(118.413 2.335 6.065)scale(1.08366 3.24985)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zpk636z_v"/><stop offset="1" class="mtfxop-pk"/></radialGradient><radialGradient id="i8JJXrd" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 0 0 28.1734 1.625 13.788)" gradientUnits="userSpaceOnUse"><stop class="sg9fyvxai"/><stop offset="1" class="r0adxvbzx"/></radialGradient><radialGradient id="imuAEBe" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.68753 -3.8615 2.52917 25.625 5.913)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="t4nmlm7ht"/><stop offset="1" class="q4q53m76f"/></radialGradient><radialGradient id="iSqBlke" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .84375 -2.45037 1.58819 23.657 6.476)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="ubeq2y34d"/><stop offset="1" class="r7flkhbpm"/></radialGradient><radialGradient id="iqPrsTK" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xli568bjl"/><stop offset="1" class="dvyuy-plf"/></radialGradient><radialGradient id="ilIh1Gd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.466 14.935 7.712)scale(3.02812 2.80781)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="aehzx_wvc"/><stop offset="1" class="x4k3qbbik"/></radialGradient><radialGradient id="i2QzoZV" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dp3nzmbzl"/><stop offset="1" class="wkrt2mblo"/></radialGradient><radialGradient id="i2vOWDd" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="i0f64nbug"/><stop offset="1" class="ucmtgi-2a"/></radialGradient><radialGradient id="i4Z432d" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.276 6.464)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="xr5reebcs"/><stop offset="1" class="z9wcvylbn"/></radialGradient><radialGradient id="ivztzoe" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.401 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zi5l5kj0o"/><stop offset="1" class="mcuv6-nuk"/></radialGradient><radialGradient id="iIpRhId" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="jwb4ndb5j"/><stop offset="1" class="iskwzzbgz"/></radialGradient><radialGradient id="iZSNaSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.078 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="n1zjiicmq"/><stop offset="1" class="h38v_uqzc"/></radialGradient><radialGradient id="iQspthd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.389)" gradientUnits="userSpaceOnUse"><stop class="r20qsbc_c"/><stop offset=".469" class="k05e99b6a"/></radialGradient><radialGradient id="icK1TWc" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="pa_nigs1j"/><stop offset="1" class="igdnfmbpz"/></radialGradient><radialGradient id="ixeCvRE" cx="0" cy="0" r="1" gradientTransform="rotate(-93.478 7.831 -4.24)scale(1.41667 3.55456)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iiOpCsb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05476 2.51663 -2.82772 -3.43237 20.35 .745)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="if2KuPc" cx="0" cy="0" r="1" gradientTransform="matrix(.2932 -1.02712 5.11536 1.46024 19.446 3.236)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iDm3fve" cx="0" cy="0" r="1" gradientTransform="rotate(-89.444 8.917 -5.005)scale(1.60945 4.07473)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iO6NXtb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49679 3.90397 -3.9658 -2.53634 19.121 .334)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="ieY1Obr" cx="0" cy="0" r="1" gradientTransform="matrix(.18011 -1.3052 4.75684 .65644 18.499 3.933)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".961" class="oxual4umn"/></radialGradient><radialGradient id="itD4eQn" cx="0" cy="0" r="1" gradientTransform="matrix(.02344 -1.14844 3.51652 .07176 13.718 4.577)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iWCAEge" cx="0" cy="0" r="1" gradientTransform="rotate(136.107 8.803 5.253)scale(2.80418 3.18917)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="ivH8TMc" cx="0" cy="0" r="1" gradientTransform="matrix(.08594 -1.03125 3.07583 .25632 18.468 4.562)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iwbexkd" cx="0" cy="0" r="1" gradientTransform="matrix(.02216 -2.11686 3.32616 .03482 13.3 5.887)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iUpGVUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.357 9.013 6.49)scale(3.42495 3.7672)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="iVi4aOc" cx="0" cy="0" r="1" gradientTransform="matrix(.11829 -1.13281 3.5915 .37502 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iDsBXSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84377 4.59374 -16.3905 -3.01059 20.85 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="kave1bcji"/><stop offset="1" class="cttfyfb4x"/></radialGradient><radialGradient id="inr4b5B" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.50682 -3.31996 -1.79016 22.82 2.882)" gradientUnits="userSpaceOnUse"><stop class="vah6rkr4l"/><stop offset="1" class="m57mo2r3b"/></radialGradient><radialGradient id="iMqJFjc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="qnsxe8b8l"/><stop offset="1" class="tiwzfl9rq"/></radialGradient><radialGradient id="iuQFhPc" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="bl99nbbnz"/><stop offset="1" class="nddsbvhqr"/></radialGradient><radialGradient id="iOz6e2d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53124 -8.125 5.12798 -2.85982 9.094 24.881)" gradientUnits="userSpaceOnUse"><stop class="x034jqb5d"/><stop offset="1" class="rpjijqwhi"/></radialGradient><radialGradient id="irIAGBv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41553 1.74219 0 18.417 13.859)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iBJQjLs" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.48812 1.85061 0 13.481 14.004)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iDHB9Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.85612 -12.0217 0 15.55 13.315)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="q7mbvrrpq"/><stop offset="1" class="e03uvcbqs"/></radialGradient><radialGradient id="iFkmeZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21324 -.68508 0 16.231 16.976)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="i9HQn0b" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 16.967 -4.508)scale(.66299 1.96142)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ij4y27d" cx="0" cy="0" r="1" gradientTransform="matrix(.11285 -.65332 1.9329 .33386 12.947 12.979)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i47nRfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87843 -1.39724 0 18.236 14.497)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="id5bUId" cx="0" cy="0" r="1" gradientTransform="matrix(-.2511 -.32358 .44549 -.3457 17.99 14.588)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7o7kwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87848 -1.39731 0 13.511 14.497)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3CofBx" cx="0" cy="0" r="1" gradientTransform="matrix(-.00838 -.53495 .64303 -.01007 13.2 14.735)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i1Jq7Zr" x1="10.735" x2="10.041" y1="15.538" y2="15.538" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iwk04Sd" x1="22.214" x2="21.327" y1="14.054" y2="16.8" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="i1ryfob" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="b9v5e-b3e"/><stop offset="1" class="t_qwphcjx"/></linearGradient><linearGradient id="iTEM0hI" x1="16.305" x2="20.382" y1="3.726" y2="3.788" gradientUnits="userSpaceOnUse"><stop class="bmtycdcmz"/><stop offset=".719" class="cu4loobdh"/></linearGradient><linearGradient id="iZpbCjj" x1="14.261" x2="10.46" y1="2.588" y2="4.774" gradientUnits="userSpaceOnUse"><stop offset=".332" class="g0a9imbkr"/><stop offset=".777" class="gv_f6obqq"/></linearGradient><linearGradient id="ikKzIbc" x1="14.299" x2="11.472" y1="2.495" y2="4.331" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="iHMsvOe" x1="18.218" x2="20.905" y1="2.499" y2="3.267" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="i74VhCe" x1="16.142" x2="21.637" y1="3.099" y2="3.827" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="ixfHMQd" x1="15.286" x2="11.971" y1="3.297" y2="4.747" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="iiety4c" x1="15.432" x2="12.281" y1="3.185" y2="4.567" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="ivIgzNd" x1="17.183" x2="20.001" y1="3.104" y2="3.444" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="is9gSbd" x1="15.17" x2="20.762" y1="4.263" y2="4.339" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="i9RlSAd" x1="14.956" x2="12.298" y1="4.165" y2="5.572" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="i868Ohe" x1="17.421" x2="19.358" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="itADcQY" x1="16.001" x2="19.946" y1="4.577" y2="4.668" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="ioyMW7d" x1="14.472" x2="11.475" y1="5.127" y2="5.94" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="i56lPRb" x1="14.505" x2="12.194" y1="5.201" y2="5.924" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="ik2Tg9d" x1="15.088" x2="11.938" y1="4.045" y2="5.427" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="iyRoKnb" x1="17.894" x2="19.781" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="ipBDPvU" x1="16.55" x2="20.282" y1="5.886" y2="5.93" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="ipBmWWm" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="tuzqszfby"/><stop offset="1" class="ljv2-xbix"/></linearGradient><linearGradient id="itisSwc" x1="20.247" x2="11.977" y1="15.658" y2="16.89" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="ioBQA6l" x1="10.033" x2="12.07" y1="18.577" y2="18.505" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iArf0Dk" x1="21.144" x2="20.001" y1="17.67" y2="17.561" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iBfhLYd" x1="10.097" x2="13.597" y1="17.858" y2="17.671" gradientUnits="userSpaceOnUse"><stop class="q5raffbaa"/><stop offset="1" class="l6kfx_2kw"/></linearGradient><linearGradient id="icnHI8b" x1="15.301" x2="24.121" y1="12.425" y2="9.268" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iWv1LZd" x1="14.941" x2="15.957" y1="16.372" y2="16.372" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iaJr89d" x1="16.893" x2="15.782" y1="16.721" y2="16.705" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iOUAAJc" x1="16.087" x2="16.087" y1="17.525" y2="16.904" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="i150MTJ" x1="16.013" x2="16.013" y1="17.57" y2="17.389" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="i9ETzte" x1="14.754" x2="15.225" y1="19.274" y2="18.529" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iNUtjtc" x1="19.078" x2="18.739" y1="14.556" y2="14.765" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPX4fre" x1="14.317" x2="13.977" y1="14.556" y2="14.765" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2PVKCb" x1="19.096" x2="18.641" y1="12.239" y2="11.309" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="icWkR3d" x1="13.351" x2="12.063" y1="12.1" y2="11.56" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i66Kgkc" x1="10.828" x2="10.828" y1="9.918" y2="12.255" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><filter id="iTfbFfc" width="3.816" height="3.616" x="8.927" y="13.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3721"/></filter><filter id="ifBnZcb" width="3.155" height="3.155" x="9.157" y="13.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".25"/></filter><filter id="iuGG3Xb" width="3.866" height="3.866" x="19.23" y="13.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3721"/></filter><filter id="iNnyvzc" width="3.155" height="3.155" x="19.46" y="13.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".25"/></filter><filter id="i1T5sIv" width="13.647" height="9.211" x="9.053" y="5.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3721"/></filter><filter id="is7bNOc" width="15.688" height="8.156" x="9.357" y="22.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".375"/></filter><filter id="i5YXg4b" width="3.938" height="1.28" x="10.688" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".125"/></filter><filter id="ikVWnac" width="3.966" height="1.018" x="11.791" y="2.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".125"/></filter><filter id="iRNid0p" width="2.922" height="1.004" x="11.925" y="4.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".125"/></filter><filter id="iY0f28c" width="3.966" height="1.018" x="11.448" y="3.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".125"/></filter><filter id="iNUBhQd" width="9.632" height="11.909" x="1.844" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".25"/></filter><filter id="iFCuFyc" width="4.094" height="4.656" x="7.923" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".25"/></filter><filter id="ikHiTbc" width="11.234" height="13.276" x="10.29" y="9.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3721"/></filter><filter id="ifoFIMe" width="8.598" height="7.321" x="14.061" y="7.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation="1"/></filter><filter id="i6IaKoc" width="3.406" height="4.404" x="13.915" y="14.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".375"/></filter><filter id="iMJrn5d" width="2.533" height="3.404" x="14.61" y="14.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".125"/></filter><filter id="iHL2pkd" width="3.206" height="1.995" x="17.157" y="11.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3721"/></filter><filter id="iwzitFc" width="3.206" height="1.995" x="11.582" y="11.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3721"/></filter><filter id="irjFete" width=".835" height=".737" x="17.45" y="14.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".05"/></filter><filter id="ilJ5oxb" width=".932" height=".956" x="18.367" y="14.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".1"/></filter><filter id="iLBBzzc" width="1.035" height="1.093" x="13.557" y="14.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".1"/></filter><filter id="iscriOe" width=".972" height=".746" x="12.731" y="14.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".05"/></filter><filter id="iF1ayed" width="3.503" height="1.967" x="16.925" y="11.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".25"/></filter><filter id="iDNClBM" width="3.587" height="2.029" x="11.273" y="11.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".25"/></filter><filter id="iqr5upd" width="1.03" height="2.395" x="10.313" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3721" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-ok-medium-dark" /></template>
<style>
.a4bll5b1e {
  d: path("m20.169 9.145l-3.333 1.11a1.134 1.134 0 0 0 .51 2.2l3.313-.443z");
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.aehzx_wvc {
  stop-color: var(--svg-color--8c6765, #8C6765);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.ati7d-krq {
  stop-color: var(--svg-color--298dff, #298DFF);
  stop-opacity: 0;
}

.b9v5e-b3e {
  stop-color: var(--svg-color--3ca8ff, #3CA8FF);
}

.bawjzlb6r {
  stop-color: var(--svg-color--298dff, #298DFF);
}

.bgx_gfbvd {
  cx: 13.217px;
  cy: 14.394px;
  rx: 0.422px;
  ry: 0.213px;
}

.bhg7_d9ul {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.285 13.687c-.707 0-1.305.487-1.467 1.146a.297.297 0 0 0 .29.369h2.416a.25.25 0 0 0 .246-.294a1.52 1.52 0 0 0-1.485-1.221");
}

.bl99nbbnz {
  stop-color: var(--svg-color--8c5e58, #8C5E58);
}

.bmtycdcmz {
  stop-color: var(--svg-color--705247, #705247);
}

.bthexfsou {
  d: path("M19.905 12.29h-.002l-.002-.002l-.004-.004l-.013-.01a2 2 0 0 0-.168-.117a3 3 0 0 0-.455-.228a3.07 3.07 0 0 0-1.616-.172a.578.578 0 0 0 .18 1.142c.43-.068.776.011 1.011.105a1.7 1.7 0 0 1 .326.172l.008.007a.578.578 0 0 0 .735-.893");
}

.btsqkkecy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.968 10.025v.972c-.009.161-.077.521-.28.674");
}

.bw3xffbxo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.167 3.374c.43-.109 2.2-.358 3.216-.233");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c4-dmkhyu {
  d: path("M19.1 14.82a.9.9 0 0 0-.251-.501l-.282.309l.127.247z");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.chsdmobsg {
  stop-color: var(--svg-color--499efa, #499EFA);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cttfyfb4x {
  stop-color: var(--svg-color--542a30, #542A30);
}

.cu4loobdh {
  stop-color: var(--svg-color--705247, #705247);
  stop-opacity: 0;
}

.cvtf9k6wz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d_3yv0zmg {
  d: path("M11.79 12.29h.002l.002-.002l.005-.004l.013-.01a2 2 0 0 1 .167-.117c.108-.068.261-.152.455-.228a3.07 3.07 0 0 1 1.616-.172a.578.578 0 0 1-.18 1.142a1.9 1.9 0 0 0-1.011.105a1.6 1.6 0 0 0-.325.172l-.009.007a.578.578 0 0 1-.735-.892");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
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

.drig65bxb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.823 4.234c.43-.11 2.2-.359 3.216-.234");
}

.dvyuy-plf {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
  stop-opacity: 0;
}

.e_u84p1_m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.675 12.134c.466-.082 1.374-.059 2.003.43");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e03uvcbqs {
  stop-color: var(--svg-color--68415b, #68415B);
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.epjcn_abj {
  cx: 21.038px;
  cy: 15.236px;
  r: 1.808px;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f0229regj {
  d: path("M7.312 5.365c-.203-.057-.676-.154-.945-.086c-.336.086-.594.329-.812.688c-.175.287-1.47 2.48-2.094 3.539c-.563.823-1.625 3.088-1.375 5.563c.1 1.662.781 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.376-5.563a915 915 0 0 0-2.094-3.54c-.218-.358-.476-.6-.812-.687c-.269-.068-.742.03-.945.086L21.5 7.53c-.352.415-.19.967-.055 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a50 50 0 0 0-1.343-.59c-.295.137-.22.125-.551.175v.29a2.307 2.307 0 1 1-4.615 0v-.384c-.298-.05-.329.076-.593-.043c-.418.155-1.092.472-1.252.552a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.135-.213.297-.765-.055-1.18z");
}

.fpbrm58zk {
  stop-color: var(--svg-color--6e5148, #6E5148);
}

.ft5dv1b6b {
  fill: none;
}

.ftdcf6bvq {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.578 15.104l-.888 1.84c-.11.379.154.757.529.757h.798c.374 0 .639-.384.529-.757l-.54-1.84c-.116-.408-.306-.408-.428 0");
}

.g0a9imbkr {
  stop-color: var(--svg-color--866253, #866253);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gmv08n5fw {
  d: path("M13.509 13.98a.966.966 0 0 0-.931 1.222h1.867a1 1 0 0 0 .035-.255a.973.973 0 0 0-.971-.966");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gv_f6obqq {
  stop-color: var(--svg-color--866253, #866253);
  stop-opacity: 0;
}

.gwwxrtb_v {
  stop-color: var(--svg-color--1d5894, #1D5894);
}

.h38v_uqzc {
  stop-color: var(--svg-color--785b4f, #785B4F);
  stop-opacity: 0;
}

.h5vigtbft {
  fill: var(--svg-color--000, #000);
  d: path("M17.685 14.947c0-.307.246-.553.553-.553a.55.55 0 0 1 .492.808h-.98a.5.5 0 0 1-.065-.255");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
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

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hxfs4uq1u {
  stop-color: var(--svg-color--826559, #826559);
  stop-opacity: 0;
}

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.i2_v3t4-e {
  stop-color: var(--svg-color--957870, #957870);
  stop-opacity: 0;
}

.i3ko4-nmt {
  d: path("m10.354 14.572l.053.002s-.058-.924-.117-1.56c0-.288.117-.635.35-.808l.173-.173c.29-.231.407-.578.407-.924v-.925c0-.288.174-.52.465-.577c.697-.173 2.149-.462 4.24-.462s3.544.289 4.24.462c.233.058.466.289.466.577v.925c0 .346.174.693.406.924c.544.38.51.59.465 1.04c-.058.577-.116 1.559-.116 1.559h.02l-.289 4.287c-.173 1.916-1.68 3.252-3.476 3.252h-3.477c-1.854 0-3.303-1.336-3.477-3.252z");
}

.i90dpqbba {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.4 18.226a.215.215 0 0 0-.258.044a.2.2 0 0 0-.021.254a2.1 2.1 0 0 0 1.756.938a2.1 2.1 0 0 0 1.756-.938a.2.2 0 0 0-.023-.256a.22.22 0 0 0-.256-.043c-.427.223-.93.35-1.477.35c-.542 0-1.05-.127-1.477-.35Z");
}

.id0lipbed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.igdnfmbpz {
  stop-color: var(--svg-color--5a4947, #5A4947);
  stop-opacity: 0;
}

.iskwzzbgz {
  stop-color: var(--svg-color--866555, #866555);
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.j664pvbhu {
  stop-color: var(--svg-color--6e5148, #6E5148);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jwb4ndb5j {
  stop-color: var(--svg-color--856152, #856152);
}

.k_ncg-saz {
  fill: var(--svg-color--352827, #352827);
  d: path("M11.79 12.29h.002l.002-.002l.005-.004l.013-.01a2 2 0 0 1 .167-.117c.108-.068.261-.152.455-.228a3.07 3.07 0 0 1 1.616-.172a.578.578 0 0 1-.18 1.142a1.9 1.9 0 0 0-1.011.105a1.6 1.6 0 0 0-.325.172l-.009.007a.578.578 0 0 1-.735-.892");
}

.k05e99b6a {
  stop-color: var(--svg-color--856253, #856253);
}

.kave1bcji {
  stop-color: var(--svg-color--542a30, #542A30);
  stop-opacity: 0;
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l2846gaef {
  stop-color: var(--svg-color--856253, #856253);
  stop-opacity: 0;
}

.l65pozi8m {
  fill: var(--svg-color--000, #000);
  d: path("M14.062 14.947a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.492.808h.98a.55.55 0 0 0 .065-.255");
}

.l6kfx_2kw {
  stop-color: var(--svg-color--7d534f, #7D534F);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9sn86auz {
  fill: var(--svg-color--352827, #352827);
  d: path("M19.905 12.29h-.002l-.002-.002l-.004-.004l-.013-.01a2 2 0 0 0-.168-.117a3 3 0 0 0-.455-.228a3.07 3.07 0 0 0-1.616-.172a.578.578 0 0 0 .18 1.142c.43-.068.776.011 1.011.105a1.7 1.7 0 0 1 .326.172l.008.007a.578.578 0 0 0 .735-.893");
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

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m57mo2r3b {
  stop-color: var(--svg-color--937262, #937262);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcuv6-nuk {
  stop-color: var(--svg-color--4298d4, #4298D4);
  stop-opacity: 0;
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mtfxop-pk {
  stop-color: var(--svg-color--43bbff, #43BBFF);
  stop-opacity: 0;
}

.n1zjiicmq {
  stop-color: var(--svg-color--785b4f, #785B4F);
}

.n9q0hl2we {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.463 14.927l-.576 1.84a.584.584 0 0 0 .564.758h.851c.4 0 .681-.385.564-.757l-.575-1.841c-.124-.408-.7-.408-.828 0");
}

.nddsbvhqr {
  stop-color: var(--svg-color--8c5e58, #8C5E58);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok_d2qbxh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.167 14.185c.07.092-.075.204-.238.327c-.164.122-.285.208-.354.116s.008-.266.171-.388c.164-.123.353-.147.421-.055");
}

.outbd-bsw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.022 12.695c.355-.313 1.128-.643 2.088-.49");
}

.oxual4umn {
  stop-color: var(--svg-color--826559, #826559);
}

.oz8qvprqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.p619n6biu {
  cx: 13.217px;
  cy: 14.394px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.422px;
  ry: 0.213px;
}

.p8vg5eein {
  cx: 10.735px;
  cy: 15.236px;
  r: 1.078px;
}

.pa_nigs1j {
  stop-color: var(--svg-color--5a4947, #5A4947);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp5mahhum {
  d: path("M14.392 14.834c0-.313-.254-.52-.323-.584l-.312.302l.192.391z");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.psmqb459k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.064 3.03c.68-.344 2.468-.57 3.187-.524");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q2wcuxbjh {
  stop-color: var(--svg-color--684034, #684034);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4q53m76f {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
  stop-opacity: 0;
}

.q4qgizelv {
  d: path("M18.167 14.185c.07.092-.075.204-.238.327c-.164.122-.285.208-.354.116s.008-.266.171-.388c.164-.123.353-.147.421-.055");
}

.q5raffbaa {
  stop-color: var(--svg-color--4f3c4a, #4F3C4A);
}

.q7mbvrrpq {
  stop-color: var(--svg-color--6d3f58, #6D3F58);
  stop-opacity: 0;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.q920b5bgt {
  stop-color: var(--svg-color--2691ff, #2691FF);
}

.qbu0-dbjp {
  stop-color: var(--svg-color--613a35, #613A35);
  stop-opacity: 0;
}

.qe_-3ab1e {
  stop-color: var(--svg-color--499efa, #499EFA);
}

.qicxwsbbh {
  d: path("M10.29 13.015c0-.29.117-.636.35-.809l.173-.173c.29-.231.407-.578.407-.924v-.925c0-.288.174-.52.465-.577c.697-.173 2.149-.462 4.24-.462s3.544.289 4.24.462c.233.058.466.289.466.577v.925c0 .346.174.693.406.924c.544.38.51.59.465 1.04c-.058.577-.116 1.559-.116 1.559h.02l-.289 4.287c-.173 1.916-1.68 3.252-3.476 3.252h-3.477c-1.854 0-3.303-1.336-3.477-3.252c-.15-1.968-.217-3.94-.396-5.904");
}

.qnsxe8b8l {
  stop-color: var(--svg-color--6d3d43, #6D3D43);
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

.r20qsbc_c {
  stop-color: var(--svg-color--9b7565, #9B7565);
}

.r7flkhbpm {
  stop-color: var(--svg-color--419ae2, #419AE2);
  stop-opacity: 0;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rl4irpj3j {
  d: path("M7.788 26.79L2.344 16.695l4.594-.812l4.038 7.877c-1.35 2.025-2.688 2.865-3.188 3.032");
}

.rmbvi9bfw {
  d: path("m21.095 8.22l.465.232c.813.404 1.278 1.328 1.104 2.31l-.64 3.292c-.056.34-.281.57-.619.578h-.02s.059-.982.117-1.56c.047-.469-.035-.612-.465-1.04c-.232-.23-.406-.577-.406-.923v-.925c0-.288-.233-.52-.465-.577c-.697-.173-2.15-.462-4.24-.462c-2.092 0-3.544.289-4.241.462a.56.56 0 0 0-.465.577v.925c0 .346-.116.693-.407.924l-.174.173c-.232.173-.348.52-.348.809c.058.635.116 1.56.116 1.56q-.027 0-.053-.003a.686.686 0 0 1-.644-.575l-.64-3.293c-.116-.924.35-1.848 1.162-2.252l.465-.231c.29-.174.581-.405.872-.636l1.045-1.097c.64-.578 1.569-.751 2.382-.347c.58.174 1.22.174 1.8 0c.872-.288 1.86-.057 2.557.578l.87.866c.233.29.524.462.872.636");
}

.rmj6-abyk {
  d: path("m15.463 14.927l-.576 1.84a.584.584 0 0 0 .564.758h.851c.4 0 .681-.385.564-.757l-.575-1.841c-.124-.408-.7-.408-.828 0");
}

.rpjijqwhi {
  stop-color: var(--svg-color--2882ff, #2882FF);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sg9fyvxai {
  stop-color: var(--svg-color--54acf3, #54ACF3);
}

.skwvwv5ha {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.462 13.687a1.51 1.51 0 0 1 1.467 1.146a.297.297 0 0 1-.29.369h-2.415a.25.25 0 0 1-.246-.294a1.51 1.51 0 0 1 1.484-1.221");
}

.spq9hx54c {
  stop-color: var(--svg-color--684034, #684034);
}

.ssq48xbfd {
  stop-color: var(--svg-color--1d5894, #1D5894);
  stop-opacity: 0;
}

.t_qwphcjx {
  stop-color: var(--svg-color--2a99ff, #2A99FF);
}

.t3eho4f7s {
  cx: 21.037px;
  cy: 15.236px;
  r: 1.078px;
}

.t4nmlm7ht {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
}

.tiwzfl9rq {
  stop-color: var(--svg-color--6d3d43, #6D3D43);
  stop-opacity: 0;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tuzqszfby {
  stop-color: var(--svg-color--3a95fa, #3A95FA);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.ubeq2y34d {
  stop-color: var(--svg-color--419ae2, #419AE2);
}

.ucmtgi-2a {
  stop-color: var(--svg-color--49abff, #49ABFF);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vah6rkr4l {
  stop-color: var(--svg-color--937262, #937262);
}

.vc8lfdbhz {
  cx: 10.735px;
  cy: 15.236px;
  r: 1.808px;
}

.veix-z38b {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.155 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wkrt2mblo {
  stop-color: var(--svg-color--1284d5, #1284D5);
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x034jqb5d {
  stop-color: var(--svg-color--2882ff, #2882FF);
}

.x4k3qbbik {
  stop-color: var(--svg-color--5b3b3e, #5B3B3E);
}

.xc55znb2x {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m21.095 8.22l.465.232c.813.404 1.278 1.328 1.104 2.31l-.64 3.292c-.056.34-.281.57-.619.578h-.02s.059-.982.117-1.56c.047-.469-.035-.612-.465-1.04c-.232-.23-.406-.577-.406-.923v-.925c0-.288-.233-.52-.465-.577c-.697-.173-2.15-.462-4.24-.462c-2.092 0-3.544.289-4.241.462a.56.56 0 0 0-.465.577v.925c0 .346-.116.693-.407.924l-.174.173c-.232.173-.348.52-.348.809c.058.635.116 1.56.116 1.56q-.027 0-.053-.003a.686.686 0 0 1-.644-.575l-.64-3.293c-.116-.924.35-1.848 1.162-2.252l.465-.231c.29-.174.581-.405.872-.636l1.045-1.097c.64-.578 1.569-.751 2.382-.347c.58.174 1.22.174 1.8 0c.872-.288 1.86-.057 2.557.578l.87.866c.233.29.524.462.872.636");
}

.xd0wwnbpf {
  d: path("M18.239 13.98a.966.966 0 0 1 .93 1.222h-1.866a.97.97 0 0 1 .935-1.221");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xli568bjl {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
}

.xr5reebcs {
  stop-color: var(--svg-color--4bb4ff, #4BB4FF);
}

.xzobpebba {
  stop-color: var(--svg-color--957870, #957870);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ygsync4_o {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.155-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z-dszxbvk {
  cx: 21.037px;
  cy: 15.236px;
  r: 1.078px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.z1x4vc35k {
  stop-color: var(--svg-color--613a35, #613A35);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z9wcvylbn {
  stop-color: var(--svg-color--347bc6, #347BC6);
}

.zi5l5kj0o {
  stop-color: var(--svg-color--4298d4, #4298D4);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
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
