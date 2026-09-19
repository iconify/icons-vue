<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iwq2hTL)"><path fill="url(#i5tycme)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#iFMhS7a)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#izE2n0c)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#ikInRTb)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#iqEPIQb)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#ikTnflc)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#iL5F81c)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#it3wfWd)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#izCyuHe)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#iUf7ftc)" clip-rule="evenodd" class="q6dtgc3jc"/><path fill="url(#iDVxKge)" clip-rule="evenodd" class="q6dtgc3jc"/></g><rect fill="url(#ivBExde)" class="iuxb-78iw"/><g filter="url(#in2a55c)"><path fill="url(#igSvB4J)" class="yzi21fb4g"/><path fill="url(#ispaMAc)" class="yzi21fb4g"/><path fill="url(#ilxYs3d)" class="yzi21fb4g"/><path fill="url(#ie0DMEq)" class="yzi21fb4g"/><path fill="url(#ihH6Xgq)" class="yzi21fb4g"/><path fill="url(#i7lYZAD)" class="yzi21fb4g"/><path fill="url(#if1SLsb)" class="yzi21fb4g"/><path fill="url(#in5Yvad)" class="yzi21fb4g"/><path fill="url(#i33AIMd)" class="yzi21fb4g"/></g><path fill="url(#iyxuAGd)" class="ggskh2bzm"/><path fill="url(#iTFLztb)" class="ggskh2bzm"/><path fill="url(#iRnp8Ge)" class="dw85flb0t"/><path fill="url(#i4oYYjb)" class="dw85flb0t"/><path fill="url(#iIpRhId)" class="xg-84-b0v"/><path fill="url(#iZSNaSd)" class="xg-84-b0v"/><path fill="url(#iQspthd)" class="p49nfmexu"/><path fill="url(#icK1TWc)" class="p49nfmexu"/><path fill="url(#iTEM0hI)" class="p49nfmexu"/><g filter="url(#iAJIc6c)"><path fill="url(#i7Zcrjd)" class="lnlk8lb5t"/></g><g filter="url(#iZPMsNe)"><path stroke="url(#iRYaePc)" class="yk5l_u5eu"/></g><path stroke="url(#iXhEgQe)" class="djebsbcjo"/><path stroke="url(#ioP46Nd)" class="djebsbcjo"/><path stroke="url(#iHMsvOe)" class="w930jqbym"/><path stroke="url(#i74VhCe)" class="w930jqbym"/><path stroke="url(#iiOpCsb)" class="w930jqbym"/><path stroke="url(#if2KuPc)" class="w930jqbym"/><path stroke="url(#ixfHMQd)" class="cvtf9k6wz"/><path stroke="url(#iDm3fve)" class="cvtf9k6wz"/><path stroke="url(#iRFH61c)" class="aj6pj94ss"/><path stroke="url(#i6CtRpd)" class="aj6pj94ss"/><path stroke="url(#iMks2Kc)" class="aj6pj94ss"/><path stroke="url(#i7EAjsd)" class="aj6pj94ss"/><path stroke="url(#i9RlSAd)" class="zw6cmm23y"/><path stroke="url(#i2bcxMb)" class="zw6cmm23y"/><path stroke="url(#i868Ohe)" class="abd3-ibar"/><path stroke="url(#itADcQY)" class="abd3-ibar"/><path stroke="url(#iWCAEge)" class="abd3-ibar"/><path stroke="url(#ivH8TMc)" class="abd3-ibar"/><path stroke="url(#irBXEGy)" class="hockzyb4d"/><path stroke="url(#ihx2kEd)" class="hockzyb4d"/><path stroke="url(#iyRoKnb)" class="lgc2wbcpd"/><path stroke="url(#ipBDPvU)" class="lgc2wbcpd"/><path stroke="url(#iUpGVUd)" class="lgc2wbcpd"/><path stroke="url(#iVi4aOc)" class="lgc2wbcpd"/><path fill="url(#iDsBXSc)" class="eim_mrbrv"/><path fill="url(#inr4b5B)" class="eim_mrbrv"/><path fill="url(#iMqJFjc)" class="r_9_ioa3h"/><path fill="url(#iuQFhPc)" class="r_9_ioa3h"/><g filter="url(#iQBW4Vd)"><path stroke="url(#iGA2skb)" class="ngb3gwb-q"/></g><g filter="url(#iGwm98t)"><path stroke="url(#imrDrSw)" class="gsuhbzbgv"/></g><g filter="url(#iXDMy5c)"><path stroke="url(#ixElTBb)" class="yztoedc1k"/></g><g filter="url(#iFY1UYd)"><path stroke="url(#ikbL4ve)" class="h-8-hirxp"/></g><g filter="url(#ieOSBfd)"><path fill="url(#iwlJozb)" class="sbubw_1vu"/></g><g filter="url(#igntj9b)"><path fill="url(#iG8w3xz)" class="y5_u3-b3g"/><path fill="url(#iIyTufG)" class="y5_u3-b3g"/></g><g filter="url(#iDoX7OV)"><path class="kipyywz8t"/><path fill="url(#iacxqqc)" class="z8678ccaz"/></g><g filter="url(#iBW2OFe)"><path class="mpjpb2bgz"/><path fill="url(#i8j3Dkv)" class="lj5lh5b7d"/></g><g filter="url(#ihHqlAc)"><path fill="url(#ivje7Od)" class="dkq0robxr"/><path fill="url(#iQLai4b)" class="dkq0robxr"/><path fill="url(#iE2tC2n)" class="dkq0robxr"/><path fill="url(#ime8Skb)" class="dkq0robxr"/><path fill="url(#icntI5c)" class="dkq0robxr"/><path fill="url(#inxyXVT)" class="dkq0robxr"/><path fill="url(#i656r8b)" class="dkq0robxr"/><path fill="url(#iJ2AGte)" class="dkq0robxr"/></g><g filter="url(#iLdc9ob)"><path class="q-48_y9kp"/></g><g filter="url(#iavcoFb)"><path class="h11cbqbte"/><path fill="url(#i4V0hGd)" class="rt09kbcly"/><path fill="url(#iFSdc9s)" class="rt09kbcly"/><path fill="url(#i06KFMd)" class="rt09kbcly"/><path fill="url(#ivzEEHc)" class="rt09kbcly"/></g><path fill="url(#iQCjzqy)" class="rt09kbcly"/><path fill="url(#igixt6c)" class="rt09kbcly"/><path stroke="url(#ibAuz6d)" class="i3-4b0bed"/><g filter="url(#ibiywdd)"><path class="byiw9vbkt"/></g><g filter="url(#igVzKyc)"><path class="rj1f_ccxr"/></g><g filter="url(#i2vHeIe)"><path class="vdnugwb4p"/></g><g filter="url(#i8xnqLc)"><path clip-rule="evenodd" class="euakfsbzl"/></g><path class="tsmo8o_up"/><path fill="url(#iUbSZwc)" class="x1l72kbuj"/><path class="a7ouvz22f"/><g filter="url(#ieCrpMb)"><path class="hr7ir7pvs"/><path fill="url(#i0EcTGc)" class="yess44bja"/></g><g filter="url(#ioLVq9c)"><path fill="url(#ih1UAkb)" class="s-miuebyy"/></g><path class="yeni5qbpl"/><path fill="url(#iSMZ7Cb)" class="qx_rgdbbw"/><path class="o_mxq2xdn"/><g filter="url(#icC3kFe)"><path fill="url(#i101nhc)" class="pwhgmyd2t"/></g><g filter="url(#i1AC5md)"><ellipse transform="rotate(-27.914 13.328 14.65)" class="oq818lret"/><ellipse fill="url(#iAvle1W)" transform="rotate(-27.914 13.328 14.65)" class="bwf7351yw"/></g><g filter="url(#i3FleOt)"><path class="qa85fjbrs"/></g><g filter="url(#iU6uQAX)"><path class="zrwkbvbbi"/></g><g filter="url(#iupsHsF)"><path class="k3_k_c3en"/><path fill="url(#iTyq5pd)" class="b5evxsgbm"/></g><g filter="url(#ilBsxDd)"><path class="sljp_-aug"/><path fill="url(#iOaOlXS)" class="ty4o8tp6l"/><path fill="url(#iayEBmM)" class="ty4o8tp6l"/></g><g filter="url(#iQfvNXM)"><path stroke="url(#idbYnci)" class="il-me-beq"/></g><g filter="url(#i8IbqOd)"><path class="l7azc39hc"/></g><defs><radialGradient id="iFMhS7a" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 -.114 15.98)scale(5.0989 6.36957)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="izE2n0c" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.47 11.168)scale(3.85551 5.06584)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ikInRTb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.468 10.47)scale(2.38628 1.83233)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iqEPIQb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.828 9.842)scale(2.7442 1.93304)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ikTnflc" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 .707 13.294)scale(3.2752 4.54648)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iL5F81c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59812 1.59823 -2.2335 -2.23334 22.515 8.787)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="it3wfWd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.04414 .5947 -1.24018 -4.2629 24.373 14.474)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="izCyuHe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.122 .78055 -.9943 -3.97697 23.704 18.265)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iUf7ftc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.86 -1.73)scale(3.10485 2.45575)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iDVxKge" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -133.36 95.528)scale(1.6766 2.71658)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ivBExde" cx="0" cy="0" r="1" gradientTransform="matrix(3.53125 2.9587 -4.23763 5.05766 14.397 21.613)" gradientUnits="userSpaceOnUse"><stop offset=".015" class="ol8_lfbrb"/><stop offset="1" class="f96ovur0y"/></radialGradient><radialGradient id="ispaMAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.23667 -6.20284 0 16 20.756)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="w58diel4g"/><stop offset="1" class="v6fmdibat"/></radialGradient><radialGradient id="ilxYs3d" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.96 8.252)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="c74g9abcg"/><stop offset=".435" class="k33dgh0kx"/></radialGradient><radialGradient id="ie0DMEq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.985 14.584)" gradientUnits="userSpaceOnUse"><stop class="yu6zwbb_v"/><stop offset=".821" class="ksxm-h6au"/></radialGradient><radialGradient id="ihH6Xgq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.772)" gradientUnits="userSpaceOnUse"><stop class="jcr-_pt7q"/><stop offset="1" class="vtkyaex6k"/></radialGradient><radialGradient id="i7lYZAD" cx="0" cy="0" r="1" gradientTransform="rotate(120.342 2.473 5.772)scale(1.39468 3.26296)" gradientUnits="userSpaceOnUse"><stop class="t_fx8fd6d"/><stop offset="1" class="u3wjuqrnp"/></radialGradient><radialGradient id="if1SLsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13764 1.26425 -3.01923 -5.10504 10.375 18.694)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="rn8u6nbre"/><stop offset="1" class="zigbbibav"/></radialGradient><radialGradient id="in5Yvad" cx="0" cy="0" r="1" gradientTransform="rotate(59.077 7.488 25.014)scale(7.31511 1.73016)" gradientUnits="userSpaceOnUse"><stop class="i01-9l3nj"/><stop offset="1" class="jyzgzgaon"/></radialGradient><radialGradient id="i33AIMd" cx="0" cy="0" r="1" gradientTransform="rotate(54.389 5.84 25.868)scale(1.53089 3.55542)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="p2il30bmc"/><stop offset="1" class="pcu2ods2z"/></radialGradient><radialGradient id="iyxuAGd" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="p96ugv3bq"/><stop offset="1" class="kaz2mfb2i"/></radialGradient><radialGradient id="iTFLztb" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="oc_nn33wh"/><stop offset="1" class="cxw9pac7i"/></radialGradient><radialGradient id="iRnp8Ge" cx="0" cy="0" r="1" gradientTransform="rotate(151.671 11.428 5.79)scale(3.23829 1.54626)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="fqnyw0bnc"/><stop offset="1" class="yysatcquz"/></radialGradient><radialGradient id="i4oYYjb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.402 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="dg25vhy-y"/><stop offset="1" class="dn15o-0do"/></radialGradient><radialGradient id="iIpRhId" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="jwb4ndb5j"/><stop offset="1" class="iskwzzbgz"/></radialGradient><radialGradient id="iZSNaSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.078 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="n1zjiicmq"/><stop offset="1" class="h38v_uqzc"/></radialGradient><radialGradient id="iQspthd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.389)" gradientUnits="userSpaceOnUse"><stop class="r20qsbc_c"/><stop offset=".469" class="k05e99b6a"/></radialGradient><radialGradient id="icK1TWc" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="pa_nigs1j"/><stop offset="1" class="igdnfmbpz"/></radialGradient><radialGradient id="i7Zcrjd" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.212 16.603)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="x733f4b8w"/><stop offset="1" class="doo06bbod"/></radialGradient><radialGradient id="ioP46Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20246 -1.95496 4.90516 -.508 12.607 3.59)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iiOpCsb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05476 2.51663 -2.82772 -3.43237 20.35 .745)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="if2KuPc" cx="0" cy="0" r="1" gradientTransform="matrix(.2932 -1.02712 5.11536 1.46024 19.446 3.236)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iDm3fve" cx="0" cy="0" r="1" gradientTransform="rotate(-89.444 8.917 -5.005)scale(1.60945 4.07473)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iMks2Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49679 3.90397 -3.9658 -2.53634 19.121 .353)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="i7EAjsd" cx="0" cy="0" r="1" gradientTransform="matrix(.18011 -1.3052 4.75684 .65644 18.499 3.953)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".961" class="oxual4umn"/></radialGradient><radialGradient id="i2bcxMb" cx="0" cy="0" r="1" gradientTransform="matrix(.02344 -1.14844 3.51652 .07176 13.718 4.577)" gradientUnits="userSpaceOnUse"><stop offset=".763" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iWCAEge" cx="0" cy="0" r="1" gradientTransform="rotate(136.107 8.803 5.253)scale(2.80418 3.18917)" gradientUnits="userSpaceOnUse"><stop offset=".748" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="ivH8TMc" cx="0" cy="0" r="1" gradientTransform="matrix(.08594 -1.03125 3.07583 .25632 18.468 4.562)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="ihx2kEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05102 -1.35157 3.65385 -.13794 13.386 5.796)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="q2wcuxbjh"/><stop offset="1" class="spq9hx54c"/></radialGradient><radialGradient id="iUpGVUd" cx="0" cy="0" r="1" gradientTransform="rotate(126.357 9.013 6.49)scale(3.42495 3.7672)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="qbu0-dbjp"/><stop offset="1" class="z1x4vc35k"/></radialGradient><radialGradient id="iVi4aOc" cx="0" cy="0" r="1" gradientTransform="matrix(.11829 -1.13281 3.5915 .37502 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="hxfs4uq1u"/><stop offset=".928" class="oxual4umn"/></radialGradient><radialGradient id="iDsBXSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84377 4.59374 -16.3905 -3.01059 20.85 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="kave1bcji"/><stop offset="1" class="cttfyfb4x"/></radialGradient><radialGradient id="inr4b5B" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.50682 -3.31996 -1.79016 22.82 2.882)" gradientUnits="userSpaceOnUse"><stop class="vah6rkr4l"/><stop offset="1" class="m57mo2r3b"/></radialGradient><radialGradient id="iMqJFjc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="qnsxe8b8l"/><stop offset="1" class="tiwzfl9rq"/></radialGradient><radialGradient id="iuQFhPc" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="bl99nbbnz"/><stop offset="1" class="nddsbvhqr"/></radialGradient><radialGradient id="iG8w3xz" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 46.976 -39.429)scale(3.03143 3.70123)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iIyTufG" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -15.116 48.266)scale(1.67237 .4728)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iacxqqc" cx="0" cy="0" r="1" gradientTransform="rotate(-4.254 219.689 -273.811)scale(1.6787 1.31228)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="i8j3Dkv" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.473 7.709)scale(1.17079)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="ivje7Od" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.983 9.52)scale(7.9405 10.6282)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iQLai4b" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.458 9.801)scale(2.64105 1.83918)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iE2tC2n" cx="0" cy="0" r="1" gradientTransform="matrix(1.42933 -4.35553 5.52636 1.81355 13.65 22.037)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="ime8Skb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4244 8.17493 -10.21854 -1.78048 17.183 14.36)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="icntI5c" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.214 9.248)scale(7.80262 13.4337)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="inxyXVT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2759 1.56588 0 18.6 14.358)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="i656r8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45523 1.6678 0 13.745 14.104)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iJ2AGte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96478 3.57762 -2.86269 -.77198 17.581 11.79)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i4V0hGd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 15.198 1.625)scale(2.32187 .71558)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ivzEEHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.86415 0 0 -.2416 16.652 17.047)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="igixt6c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52032 1.04375 -1.25442 -1.82718 16.466 16.388)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iUbSZwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89954 -1.43081 0 18.467 14.756)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0EcTGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25713 -.33135 .4562 -.35401 18.214 14.849)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSMZ7Cb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89954 -1.43082 0 13.629 14.756)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iAvle1W" cx="0" cy="0" r="1" gradientTransform="matrix(-.00858 -.54778 .65846 -.0103 13.31 14.998)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTyq5pd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39929 -3.05504 1.56288 .71584 9.774 12.405)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iOaOlXS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3416 4.86897 -7.96048 -3.82838 18.166 6.631)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iayEBmM" cx="0" cy="0" r="1" gradientTransform="matrix(-.2332 1.51587 -3.2613 -.50173 16.28 7.04)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iwq2hTL" width="16.901" height="17.401" x="7.722" y="5.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="in2a55c" width="28.403" height="24.735" x="2.048" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.25098 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="iAJIc6c" width="16.188" height="8.656" x="9.173" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".5"/></filter><filter id="iZPMsNe" width="3.994" height="4.556" x="7.973" y="22.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".25"/></filter><filter id="iQBW4Vd" width="3.508" height="1.177" x="11.476" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".125"/></filter><filter id="iGwm98t" width="4.103" height="1.115" x="11.342" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".125"/></filter><filter id="iXDMy5c" width="4.103" height="1.115" x="11.476" y="2.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".125"/></filter><filter id="iFY1UYd" width="4.288" height="1.471" x="10.461" y="1.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".125"/></filter><filter id="ieOSBfd" width="3.718" height="3.568" x="9.069" y="13.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="igntj9b" width="3.568" height="3.818" x="19.616" y="13.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="iDoX7OV" width="3.382" height="3.382" x="19.709" y="13.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".25"/></filter><filter id="iBW2OFe" width="2.882" height="2.882" x="9.433" y="13.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".125"/></filter><filter id="ihHqlAc" width="11.299" height="12.46" x="10.398" y="9.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="iLdc9ob" width="3.081" height="3.973" x="14.327" y="14.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".25"/></filter><filter id="iavcoFb" width="2.581" height="3.473" x="14.757" y="14.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".125"/></filter><filter id="ibiywdd" width="3.306" height="1.425" x="17.114" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="igVzKyc" width="3.306" height="1.425" x="11.676" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="i2vHeIe" width="2.698" height="1.188" x="11.825" y="12.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="i8xnqLc" width="2.698" height="1.188" x="17.832" y="12.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/></filter><filter id="ieCrpMb" width=".851" height=".75" x="17.664" y="14.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".05"/></filter><filter id="ioLVq9c" width=".945" height=".969" x="18.606" y="14.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".1"/></filter><filter id="icC3kFe" width="1.05" height="1.11" x="13.68" y="14.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".1"/></filter><filter id="i1AC5md" width=".991" height=".759" x="12.832" y="14.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".05"/></filter><filter id="i3FleOt" width="2.641" height="1.219" x="17.798" y="12.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".1"/></filter><filter id="iU6uQAX" width="2.441" height="1.019" x="11.854" y="12.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".1"/></filter><filter id="iupsHsF" width="4.583" height="4.917" x="9.146" y="7.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/><feGaussianBlur result="effect2_foregroundBlur_4002_3720" stdDeviation=".15"/></filter><filter id="ilBsxDd" width="9.711" height="6.456" x="12.565" y="6.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3720"/><feGaussianBlur result="effect2_foregroundBlur_4002_3720" stdDeviation=".15"/></filter><filter id="iQfvNXM" width="1.204" height="2.496" x="12.542" y="7.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".1"/></filter><filter id="i8IbqOd" width="6.963" height="3.576" x="15.484" y="8.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3720" stdDeviation=".375"/></filter><linearGradient id="i5tycme" x1="21.251" x2="13.706" y1="7.709" y2="21.684" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="igSvB4J" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="ny7dycfhy"/><stop offset="1" class="xhpdgtb4r"/></linearGradient><linearGradient id="iTEM0hI" x1="16.305" x2="20.382" y1="3.726" y2="3.788" gradientUnits="userSpaceOnUse"><stop class="bmtycdcmz"/><stop offset=".719" class="cu4loobdh"/></linearGradient><linearGradient id="iRYaePc" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="zxa4g21za"/><stop offset="1" class="py_i1i4hl"/></linearGradient><linearGradient id="iXhEgQe" x1="14.261" x2="10.46" y1="2.588" y2="4.774" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="iHMsvOe" x1="18.218" x2="20.905" y1="2.499" y2="3.267" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="i74VhCe" x1="16.142" x2="21.637" y1="3.099" y2="3.827" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="ixfHMQd" x1="15.286" x2="11.971" y1="3.297" y2="4.747" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="iRFH61c" x1="17.183" x2="20.001" y1="3.124" y2="3.463" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="i6CtRpd" x1="15.17" x2="20.762" y1="4.282" y2="4.359" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="i9RlSAd" x1="14.956" x2="12.298" y1="4.165" y2="5.572" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="i868Ohe" x1="17.421" x2="19.358" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="itADcQY" x1="16.001" x2="19.946" y1="4.577" y2="4.668" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="irBXEGy" x1="14.472" x2="11.788" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g0a9imbkr"/><stop offset="1" class="gv_f6obqq"/></linearGradient><linearGradient id="iyRoKnb" x1="17.894" x2="19.781" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="k05e99b6a"/><stop offset="1" class="l2846gaef"/></linearGradient><linearGradient id="ipBDPvU" x1="16.55" x2="20.282" y1="5.886" y2="5.93" gradientUnits="userSpaceOnUse"><stop class="fpbrm58zk"/><stop offset=".844" class="j664pvbhu"/></linearGradient><linearGradient id="iGA2skb" x1="14.651" x2="11.599" y1="5.259" y2="5.98" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="imrDrSw" x1="15.121" x2="11.6" y1="4.207" y2="5.388" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="ixElTBb" x1="15.255" x2="11.734" y1="3.221" y2="4.402" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="ikbL4ve" x1="14.436" x2="11.189" y1="2.409" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="xzobpebba"/><stop offset="1" class="i2_v3t4-e"/></linearGradient><linearGradient id="iwlJozb" x1="9.125" x2="10.501" y1="15.514" y2="15.514" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iFSdc9s" x1="15.007" x2="16.048" y1="16.894" y2="16.894" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i06KFMd" x1="16.048" x2="16.048" y1="17.779" y2="17.103" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iQCjzqy" x1="16.134" x2="16.134" y1="17.75" y2="17.596" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="ibAuz6d" x1="14.868" x2="15.379" y1="19.343" y2="18.553" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ih1UAkb" x1="19.33" x2="18.982" y1="14.816" y2="15.03" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i101nhc" x1="14.453" x2="14.105" y1="14.815" y2="15.03" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idbYnci" x1="12.842" x2="13.446" y1="8.545" y2="9.958" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-ok-medium-dark" /></template>
<style>
.a7ouvz22f {
  fill: var(--svg-color--000, #000);
  d: path("M17.903 15.216c0-.314.252-.566.566-.566a.564.564 0 0 1 .504.827H17.97a.5.5 0 0 1-.067-.26");
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.aj6pj94ss {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.627c-.43-.11-2.375-.477-3.255-.266");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b5evxsgbm {
  d: path("M10.427 8.778c.628-.664 1.815-.665 2.363-.566l.439 1.43c-.28-.042-.53.057-.74.261c-.498 1.398-2.206 2.168-2.999 2.379c-.164-1.654.121-2.64.937-3.504");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bl99nbbnz {
  stop-color: var(--svg-color--8c5e58, #8C5E58);
}

.bmtycdcmz {
  stop-color: var(--svg-color--705247, #705247);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bwf7351yw {
  cx: 13.328px;
  cy: 14.65px;
  rx: 0.432px;
  ry: 0.219px;
}

.byiw9vbkt {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.314 14.787c.294-.518.742-.927 1.705-.927c.421 0 .828.117 1.189.41c.298.24.258.548.027.664l-.616.352c-.723-.234-1.522-.266-2.305-.5");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c74g9abcg {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
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

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cttfyfb4x {
  stop-color: var(--svg-color--542a30, #542A30);
}

.cu4loobdh {
  stop-color: var(--svg-color--705247, #705247);
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

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
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

.dkq0robxr {
  d: path("M10.407 14.018h.014l-.011-.294l-.012-.34c.023-1.052.637-1.46.898-1.595l.057-.022l.057-.023a2.55 2.55 0 0 0 1.319-1.369l.091-.215a.292.292 0 0 1 .512-.056a4.28 4.28 0 0 0 3.536 1.855h3.57c.2 0 1.2.097 1.26 1.477l-.133 3.407c-.136 3.107-2.563 5.194-5.525 5.194c-2.961 0-5.388-2.087-5.525-5.194z");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dn15o-0do {
  stop-color: var(--svg-color--584b8c, #584B8C);
  stop-opacity: 0;
}

.doo06bbod {
  stop-color: var(--svg-color--9179cd, #9179CD);
  stop-opacity: 0;
}

.dw85flb0t {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.156-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.euakfsbzl {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m20.185 12.94l-.153.254za.297.297 0 0 1-.306.51l-.005-.002l-.024-.014l-.1-.051a3 3 0 0 0-.38-.15a2.5 2.5 0 0 0-1.19-.102a.297.297 0 1 1-.102-.585c.568-.1 1.095 0 1.472.12a3.6 3.6 0 0 1 .584.245l.035.02l.01.006l.004.002h.001z");
}

.f96ovur0y {
  stop-color: var(--svg-color--8e6864, #8E6864);
}

.fpbrm58zk {
  stop-color: var(--svg-color--6e5148, #6E5148);
}

.fqnyw0bnc {
  stop-color: var(--svg-color--8378b6, #8378B6);
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0a9imbkr {
  stop-color: var(--svg-color--866253, #866253);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ggskh2bzm {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.156 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
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

.gv_f6obqq {
  stop-color: var(--svg-color--866253, #866253);
  stop-opacity: 0;
}

.h-8-hirxp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.836 3.08c.433-.236 2.032-.622 3.538-.722");
}

.h11cbqbte {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.624 15.017l-.59 1.885a.598.598 0 0 0 .578.775h.872a.6.6 0 0 0 .577-.775l-.59-1.885c-.126-.417-.715-.417-.847 0");
}

.h38v_uqzc {
  stop-color: var(--svg-color--785b4f, #785B4F);
  stop-opacity: 0;
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hr7ir7pvs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.397 14.436c.07.094-.077.21-.245.335s-.292.213-.362.119c-.07-.095.008-.273.175-.398c.168-.125.361-.15.431-.056");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hxfs4uq1u {
  stop-color: var(--svg-color--826559, #826559);
  stop-opacity: 0;
}

.i01-9l3nj {
  stop-color: var(--svg-color--9478d2, #9478D2);
}

.i2_v3t4-e {
  stop-color: var(--svg-color--957870, #957870);
  stop-opacity: 0;
}

.i3-4b0bed {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.891 18.534a.215.215 0 0 0-.023-.27a.22.22 0 0 0-.267-.045a3.3 3.3 0 0 1-1.553.377a3.3 3.3 0 0 1-1.553-.376a.22.22 0 0 0-.268.047a.21.21 0 0 0-.022.268m3.686 0l-.042-.028l.042.027Zm0 0a2.192 2.192 0 0 1-3.686 0m0 0l.041-.028m-.041.027l.041-.027m0 0a2.142 2.142 0 0 0 3.603 0c.098-.15-.07-.324-.225-.243a3.34 3.34 0 0 1-1.576.382c-.578 0-1.12-.14-1.576-.382c-.156-.081-.324.098-.226.243Z");
}

.igdnfmbpz {
  stop-color: var(--svg-color--5a4947, #5A4947);
  stop-opacity: 0;
}

.il-me-beq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.842 8.164c.026.27.26 1.283.604 1.896");
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

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j664pvbhu {
  stop-color: var(--svg-color--6e5148, #6E5148);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jcr-_pt7q {
  stop-color: var(--svg-color--7357b2, #7357B2);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jwb4ndb5j {
  stop-color: var(--svg-color--856152, #856152);
}

.jyzgzgaon {
  stop-color: var(--svg-color--9478d2, #9478D2);
  stop-opacity: 0;
}

.k05e99b6a {
  stop-color: var(--svg-color--856253, #856253);
}

.k3_k_c3en {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.427 8.778c.628-.664 1.815-.665 2.363-.566l.439 1.43c-.28-.042-.53.057-.74.261c-.498 1.398-2.206 2.168-2.999 2.379c-.164-1.654.121-2.64.937-3.504");
}

.k33dgh0kx {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
  stop-opacity: 0;
}

.kave1bcji {
  stop-color: var(--svg-color--542a30, #542A30);
  stop-opacity: 0;
}

.kaz2mfb2i {
  stop-color: var(--svg-color--4c4181, #4C4181);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kipyywz8t {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M21.4 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.ksxm-h6au {
  stop-color: var(--svg-color--65509d, #65509D);
  stop-opacity: 0;
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l2846gaef {
  stop-color: var(--svg-color--856253, #856253);
  stop-opacity: 0;
}

.l7azc39hc {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.716 10.782l-1.58.29a.763.763 0 1 1-.14-1.512h2.596c1.535 0 2.043 1.547 2.105 2.075a3.49 3.49 0 0 0-2.981-.853");
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

.lj5lh5b7d {
  d: path("M10.874 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lnlk8lb5t {
  d: path("M23.939 27.147c-1.95-1.2-3.037-3.417-3.36-4.157c-5.175 0-9.281 1.97-10.406 6.657H24.36c0-.9-.156-1.938-.421-2.5");
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

.mpjpb2bgz {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M10.874 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1zjiicmq {
  stop-color: var(--svg-color--785b4f, #785B4F);
}

.nddsbvhqr {
  stop-color: var(--svg-color--8c5e58, #8C5E58);
  stop-opacity: 0;
}

.ngb3gwb-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 5.561c.392-.173 1.476-.503 2.759-.41");
}

.ny7dycfhy {
  stop-color: var(--svg-color--7767af, #7767AF);
}

.o_mxq2xdn {
  fill: var(--svg-color--000, #000);
  d: path("M14.193 15.216a.564.564 0 0 0-.567-.566a.564.564 0 0 0-.504.827h1.003a.56.56 0 0 0 .068-.26");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.oc_nn33wh {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ol8_lfbrb {
  stop-color: var(--svg-color--5a313a, #5A313A);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.oq818lret {
  cx: 13.328px;
  cy: 14.65px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.432px;
  ry: 0.219px;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oxual4umn {
  stop-color: var(--svg-color--826559, #826559);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p2il30bmc {
  stop-color: var(--svg-color--694eab, #694EAB);
}

.p49nfmexu {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.592-.465.81-.46l.135-.196c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
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

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwhgmyd2t {
  d: path("M14.53 15.1c0-.32-.26-.533-.33-.597l-.32.309l.197.4z");
}

.py_i1i4hl {
  stop-color: var(--svg-color--8477ba, #8477BA);
  stop-opacity: 0;
}

.q-48_y9kp {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.613 15.17l-.758 1.886a.598.598 0 0 0 .577.775h.872a.6.6 0 0 0 .577-.775l-.59-1.885c-.126-.418-.546-.418-.678 0");
}

.q2wcuxbjh {
  stop-color: var(--svg-color--684034, #684034);
  stop-opacity: 0;
}

.q6dtgc3jc {
  fill-rule: evenodd;
  d: path("M24.014 16.98c.236-.482.36-1.02.36-1.581a3.6 3.6 0 0 0-.298-1.448h.005c-.089-.2-.189-.39-.311-.569l-.003-.003a3.6 3.6 0 0 1-.583-1.964v-.01a3.66 3.66 0 0 0-3.658-3.659a.6.6 0 0 1-.505-.258a3.67 3.67 0 0 0-2.973-1.526a3.67 3.67 0 0 0-2.974 1.526a.63.63 0 0 1-.505.258l-.094.001a3.66 3.66 0 0 0-3.564 3.657v.011c0 .696-.202 1.38-.583 1.964l-.003.004a3.66 3.66 0 0 0-.244 3.598a.57.57 0 0 1 0 .505a3.6 3.6 0 0 0-.359 1.56a3.563 3.563 0 0 0 3.568 3.567h9.515a3.563 3.563 0 0 0 3.568-3.568a3.6 3.6 0 0 0-.359-1.56a.57.57 0 0 1 0-.504m-13.593-2.962h-.014l1.33 2.611c.136 3.108 1.349 0 4.31 0c2.963 0 4.254 3.459 4.39.352l1.26-3.545c-.06-1.38-1.06-1.477-1.26-1.477h-3.57a4.28 4.28 0 0 1-3.535-1.855a.292.292 0 0 0-.512.056l-.09.215a2.56 2.56 0 0 1-1.32 1.369l-.057.023l-.056.022c-.262.136-.876.543-.899 1.595l.012.34z");
}

.qa85fjbrs {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.198 12.787c.358-.087 1.247-.043 1.842.382");
}

.qbu0-dbjp {
  stop-color: var(--svg-color--613a35, #613A35);
  stop-opacity: 0;
}

.qnsxe8b8l {
  stop-color: var(--svg-color--6d3d43, #6D3D43);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qx_rgdbbw {
  d: path("M13.626 14.227a.99.99 0 0 0-.953 1.25h1.911q.035-.126.036-.26a.996.996 0 0 0-.994-.99");
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r20qsbc_c {
  stop-color: var(--svg-color--9b7565, #9B7565);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rj1f_ccxr {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.782 14.787c-.295-.518-.742-.927-1.705-.927c-.421 0-.828.117-1.19.41c-.297.24-.258.548-.027.664l.617.352c.723-.234 1.522-.266 2.305-.5");
}

.rn8u6nbre {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
}

.rt09kbcly {
  d: path("m15.624 15.017l-.59 1.885a.598.598 0 0 0 .578.775h.872a.6.6 0 0 0 .577-.775l-.59-1.885c-.126-.417-.715-.417-.847 0");
}

.s-miuebyy {
  d: path("M19.35 15.086a.93.93 0 0 0-.256-.513l-.288.316l.13.253z");
}

.sbubw_1vu {
  d: path("M10.853 17.202a1.784 1.784 0 1 0 0-3.568a1.784 1.784 0 0 0 0 3.568");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sljp_-aug {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.379 6.78c-1.256-.277-2.384.976-2.514 1.44c1.166 3.93 4.117 3.715 7.03 3.392c1.743-.194 1.932.6 2.081.985c0-4.36-3.708-5.18-6.565-5.81z");
}

.spq9hx54c {
  stop-color: var(--svg-color--684034, #684034);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t_fx8fd6d {
  stop-color: var(--svg-color--9179c9, #9179C9);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tiwzfl9rq {
  stop-color: var(--svg-color--6d3d43, #6D3D43);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsmo8o_up {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.699 13.926c.724 0 1.335.499 1.502 1.173a.304.304 0 0 1-.297.378H17.43a.255.255 0 0 1-.252-.301a1.55 1.55 0 0 1 1.52-1.25");
}

.ty4o8tp6l {
  d: path("M15.379 6.78c-1.256-.277-2.384.976-2.514 1.44c1.166 3.93 4.117 3.715 7.03 3.392c1.743-.194 1.932.6 2.081.985c0-4.36-3.708-5.18-6.565-5.81z");
}

.u3wjuqrnp {
  stop-color: var(--svg-color--9179c9, #9179C9);
  stop-opacity: 0;
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v6fmdibat {
  stop-color: var(--svg-color--312654, #312654);
  stop-opacity: 0;
}

.vah6rkr4l {
  stop-color: var(--svg-color--937262, #937262);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vdnugwb4p {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.28 13.447l-.004.002a.298.298 0 0 1-.306-.51h.002l.003-.003l.01-.006a2 2 0 0 1 .165-.085a4 4 0 0 1 .455-.18c.377-.12.904-.22 1.472-.12a.297.297 0 1 1-.103.585c-.442-.078-.867 0-1.188.102a3 3 0 0 0-.505.215");
}

.vtkyaex6k {
  stop-color: var(--svg-color--7357b2, #7357B2);
  stop-opacity: 0;
}

.w58diel4g {
  stop-color: var(--svg-color--312654, #312654);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x1l72kbuj {
  d: path("M18.47 14.227a.99.99 0 0 1 .953 1.25H17.51a.993.993 0 0 1 .958-1.25");
}

.x733f4b8w {
  stop-color: var(--svg-color--9179cd, #9179CD);
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

.xzobpebba {
  stop-color: var(--svg-color--957870, #957870);
}

.y5_u3-b3g {
  d: path("M21.4 17.202a1.784 1.784 0 1 0 0-3.568a1.784 1.784 0 0 0 0 3.568");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.yeni5qbpl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.397 13.926c-.724 0-1.336.499-1.502 1.173a.304.304 0 0 0 .296.378h2.474a.255.255 0 0 0 .252-.301a1.554 1.554 0 0 0-1.52-1.25");
}

.yess44bja {
  d: path("M18.397 14.436c.07.094-.077.21-.245.335s-.292.213-.362.119c-.07-.095.008-.273.175-.398c.168-.125.361-.15.431-.056");
}

.yk5l_u5eu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
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

.z1x4vc35k {
  stop-color: var(--svg-color--613a35, #613A35);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z8678ccaz {
  d: path("M21.4 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.zigbbibav {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
  stop-opacity: 0;
}

.zrwkbvbbi {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.995 12.787c-.358-.087-1.247-.043-1.841.382");
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.zxa4g21za {
  stop-color: var(--svg-color--8477ba, #8477BA);
}

</style>
