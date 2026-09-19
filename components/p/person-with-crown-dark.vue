<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4X6gQb)" class="yq4cmdu2g"/><path fill="url(#iP6PLfc)" class="yq4cmdu2g"/><path fill="url(#iQIno6d)" class="z9ftlqvnr"/><path fill="url(#iBGggtc)" class="z9ftlqvnr"/><path fill="url(#iMyPqOK)" class="us1u98b3g"/><path fill="url(#iwSpWAe)" class="us1u98b3g"/><g filter="url(#iDpLQQd)"><path class="m3xuw6x7t"/><path class="j8vxk9r3t"/></g><g filter="url(#ikUYV5c)"><path class="ncr9djbkt"/><path class="i3n99zbcs"/></g><path class="q8zps5bkz"/><path fill="url(#iKpNxNi)" class="ay11wq5le"/><path fill="url(#i3SQbDe)" class="ay11wq5le"/><path fill="url(#iyxEWTc)" class="ay11wq5le"/><circle fill="url(#iZ3BMQx)" class="kfayvkisl"/><g filter="url(#iirk3Rb)"><path fill="url(#iBCta6d)" class="d3e9_irck"/><path fill="url(#iIKZtAe)" class="d3e9_irck"/><path fill="url(#iHMIXWh)" class="d3e9_irck"/></g><path fill="url(#iZHjg3d)" class="f8xv78wwh"/><path fill="url(#iB7870d)" class="f8xv78wwh"/><path fill="url(#iZFhrYb)" class="f8xv78wwh"/><path fill="url(#i0cYndb)" class="f8xv78wwh"/><path fill="url(#iqJUymd)" class="f8xv78wwh"/><g filter="url(#iQFOz3x)"><path fill="url(#iloAeIb)" class="vmhbtsb-a"/><path fill="url(#iIfxIeM)" class="vmhbtsb-a"/><path fill="url(#iluDLDc)" class="vmhbtsb-a"/><path fill="url(#i3YmUdc)" class="vmhbtsb-a"/></g><path fill="url(#irUks1b)" class="shgrjqbiz"/><path fill="url(#i5Cpwir)" class="shgrjqbiz"/><path fill="url(#ivjzpvb)" class="shgrjqbiz"/><path fill="url(#irBmJac)" class="shgrjqbiz"/><path fill="url(#iwNBtlc)" class="shgrjqbiz"/><g filter="url(#iWkesTd)"><path fill="url(#iG44IVc)" class="rnq8zfbyk"/><path fill="url(#iAyKCmx)" class="rnq8zfbyk"/><path fill="url(#ireDgWd)" class="rnq8zfbyk"/><path fill="url(#itK9dec)" class="rnq8zfbyk"/></g><path fill="url(#iFaPctd)" class="kiolp_-pe"/><path fill="url(#iNOiLgd)" class="kiolp_-pe"/><path fill="url(#iN3ekpY)" class="kiolp_-pe"/><path fill="url(#iXRpDRc)" class="kiolp_-pe"/><path fill="url(#i9czF6b)" class="kiolp_-pe"/><g filter="url(#iRYXdoe)"><path fill="url(#iNFHMKc)" class="swjgceb9v"/><path fill="url(#iYIbosd)" class="swjgceb9v"/><path fill="url(#iBeQbPb)" class="swjgceb9v"/><path fill="url(#iWwOBIc)" class="swjgceb9v"/></g><path fill="url(#idZzGvb)" class="kbcpr6bot"/><path fill="url(#iBIanRb)" class="kbcpr6bot"/><path fill="url(#iwVkT9d)" class="kbcpr6bot"/><path fill="url(#iYF91vc)" class="kbcpr6bot"/><path fill="url(#iqvKkkc)" class="kbcpr6bot"/><g filter="url(#ijjjync)"><path fill="url(#ibWAHoB)" class="escp53_pi"/><path fill="url(#ixyyVtb)" class="escp53_pi"/><path fill="url(#iUz1GON)" class="escp53_pi"/><path fill="url(#iNF4hvc)" class="escp53_pi"/></g><path fill="url(#i0qGmeT)" class="c0g3mbbdp"/><path fill="url(#imRqQGW)" class="c0g3mbbdp"/><path fill="url(#iqIlRze)" class="c0g3mbbdp"/><path fill="url(#iraNcty)" class="c0g3mbbdp"/><g filter="url(#ibUZJNc)"><path fill="url(#i8a7U2b)" class="fw-_ge0oq"/></g><g filter="url(#iQFSIOd)"><path fill="url(#iamWsYd)" class="sgtr8ibeb"/><path fill="url(#iH7WSsc)" class="sgtr8ibeb"/></g><g filter="url(#i6Sit9c)"><circle fill="url(#iejUKqO)" class="we5kvqbpm"/><circle fill="url(#iz3N9Og)" class="we5kvqbpm"/></g><ellipse fill="url(#iLmTvNj)" class="i5vxhhb9k"/><ellipse fill="url(#iWOFObc)" class="i5vxhhb9k"/><circle fill="url(#iLnMLcb)" class="f-t10ph2f"/><g filter="url(#iydwbUb)"><path fill="url(#iFbzqEd)" class="j9g9dbhkm"/></g><g filter="url(#iCga5yd)"><circle fill="url(#ilMc2me)" class="f19u2wb6f"/><circle fill="url(#iDgYjte)" class="f19u2wb6f"/></g><g filter="url(#iulOqbc)"><path fill="url(#iOspXqd)" class="zb7wmmorx"/><path fill="url(#i6HCwxb)" class="zb7wmmorx"/></g><g filter="url(#iMk0Slc)"><circle fill="url(#iHTVxLe)" class="qk8v1bc2n"/><circle fill="url(#iprWAmd)" class="qk8v1bc2n"/></g><circle fill="url(#ia01BWX)" class="ewitywhfr"/><circle fill="url(#iNe5Amc)" class="ewitywhfr"/><circle fill="url(#iPsaLGe)" class="azdozg41y"/><circle fill="url(#ijQY9Cb)" class="azdozg41y"/><path fill="url(#ip37IoS)" class="t0v0fubzw"/><path fill="url(#itFCeSb)" class="ydfb--rgm"/><g filter="url(#idy4Ucc)"><path fill="url(#i5F8Rnb)" class="j0o8lia9p"/></g><path fill="url(#iYhr0Zc)" class="j0o8lia9p"/><path fill="url(#iYYp79C)" class="j0o8lia9p"/><path fill="url(#iuEj4hc)" class="j0o8lia9p"/><path fill="url(#imccyNb)" class="j0o8lia9p"/><path fill="url(#i9ATRgb)" class="j0o8lia9p"/><path fill="url(#iPRLDTk)" class="j0o8lia9p"/><path fill="url(#icXsFqc)" class="j0o8lia9p"/><path fill="url(#ii5waYd)" class="j0o8lia9p"/><path fill="url(#ir6pTOb)" class="j0o8lia9p"/><g filter="url(#iWRB15c)"><path class="sv01lobuk"/></g><g filter="url(#iAsGSnd)"><path class="xt4ezwz_m"/><path fill="url(#iisl1Eb)" class="yn34xubbb"/><path fill="url(#igipFGc)" class="yn34xubbb"/><path fill="url(#iuRhSNc)" class="yn34xubbb"/><path fill="url(#ihAG6pc)" class="yn34xubbb"/><path fill="url(#iwJJ10b)" class="yn34xubbb"/></g><g filter="url(#i7YHmEh)"><path stroke="url(#iKzXIQN)" class="v65_ahc-c"/></g><path fill="url(#iomKFWb)" class="z01xu_6ui"/><path class="g5wpc5oah"/><path fill="url(#iPdusZt)" class="ryyd73bhi"/><path class="z0o3egbpm"/><g filter="url(#iwFrbud)"><path class="ipe5nqbjx"/><path fill="url(#ifjTTDb)" class="fj7de7bxl"/></g><g filter="url(#iiSCjad)"><path fill="url(#iU5Kkqc)" class="vuv5a3b-t"/></g><path class="i6zt6f36k"/><path fill="url(#iUaGWGc)" class="y6o_a1bwr"/><path class="u_l38sbak"/><g filter="url(#iV8sSlj)"><path fill="url(#ikju3Mc)" class="p691-zb3j"/></g><g filter="url(#iTaktuT)"><ellipse transform="rotate(-27.914 13.54 13.937)" class="n5q_2-c9z"/><ellipse fill="url(#ixqWmrd)" transform="rotate(-27.914 13.54 13.937)" class="k8wj80bfs"/></g><path fill="url(#iZdHeme)" class="ww_ne9n0y"/><path fill="url(#ihMlInc)" class="ww_ne9n0y"/><path fill="url(#iDoM3hd)" class="ww_ne9n0y"/><path fill="url(#iT7PiAe)" class="ww_ne9n0y"/><path fill="url(#igBNEkc)" class="t4qznn7ln"/><path fill="url(#iEGSCde)" class="t4qznn7ln"/><g filter="url(#ifddBxs)"><path fill="url(#itBKuEJ)" class="ekzgfq9bb"/></g><g filter="url(#iqNhqHe)"><path fill="url(#iPVmwDe)" class="uuabbt8jv"/></g><path fill="url(#iq31Hcc)" class="gaqflu3bm"/><path fill="url(#iovwq8b)" class="gaqflu3bm"/><path fill="url(#igPCvHd)" class="gaqflu3bm"/><path fill="url(#iSEn53b)" class="gaqflu3bm"/><path fill="url(#iwwfhfb)" class="gaqflu3bm"/><path fill="url(#iF22uOe)" class="gaqflu3bm"/><path fill="url(#izco7cb)" class="gaqflu3bm"/><path fill="url(#i8z60vd)" class="gaqflu3bm"/><path fill="url(#iDBZL0c)" class="gaqflu3bm"/><path fill="url(#iZDC2xd)" class="gaqflu3bm"/><path fill="url(#iaxQkid)" class="gaqflu3bm"/><g filter="url(#iF1u09b)"><circle fill="url(#iCJwfdb)" class="jzfasvbbp"/><circle fill="url(#ixiw7Nc)" class="jzfasvbbp"/></g><g filter="url(#iU8EcFb)"><circle fill="url(#i2Kf17d)" class="ldyj_nb1e"/><circle fill="url(#iyXQn0l)" class="ldyj_nb1e"/></g><g filter="url(#icNzjEc)"><circle fill="url(#iwdleKr)" class="t3kcpjbyb"/><circle fill="url(#iFovmgd)" class="t3kcpjbyb"/><circle fill="url(#ia6Q7le)" class="t3kcpjbyb"/></g><g filter="url(#ijx6hcc)"><circle fill="url(#iUCPwrb)" class="n4msb7ugs"/><circle fill="url(#iC0wJeI)" class="n4msb7ugs"/></g><g filter="url(#in9Rmyb)"><circle fill="url(#iZfcJcb)" class="pxse0-u4m"/><circle fill="url(#iubs2De)" class="pxse0-u4m"/></g><g filter="url(#iiwggqb)"><path stroke="url(#iGnutIe)" class="jk0mh1bxi"/></g><g filter="url(#igTFtXc)"><path stroke="url(#ixEacre)" class="cqs57sk5v"/></g><g filter="url(#ibjfADd)"><path stroke="url(#iSbcJUc)" class="lll2sghve"/></g><g filter="url(#inoPYoe)"><circle fill="url(#ifvdSwb)" class="kowfi484h"/><circle fill="url(#iHZGaVd)" class="kowfi484h"/></g><circle fill="url(#iwpylec)" class="kowfi484h"/><defs><radialGradient id="i4X6gQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.5625 -14.1309 0 16 22.402)" gradientUnits="userSpaceOnUse"><stop class="vsg8c7gji"/><stop offset=".542" class="x9knvh_3c"/></radialGradient><radialGradient id="iP6PLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9375 0 0 -23.6312 23.807 29.964)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="q5a0_7mqo"/><stop offset="1" class="rrwvrg1ho"/></radialGradient><radialGradient id="iQIno6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.28332 4.28735 0 8.354 29.67)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="fsr110b8t"/><stop offset="1" class="jo4sxnm8i"/></radialGradient><radialGradient id="iMyPqOK" cx="0" cy="0" r="1" gradientTransform="matrix(3.36005 0 0 6.32267 23.847 28.93)" gradientUnits="userSpaceOnUse"><stop class="u_7404bbu"/><stop offset="1" class="v4gg9p-ym"/></radialGradient><radialGradient id="iyxEWTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .69531 -2.16649 0 16.006 23.956)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="o_4gny8-z"/><stop offset=".622" class="jrd3jzgth"/></radialGradient><radialGradient id="iZ3BMQx" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 2.282 18.291)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="iIKZtAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 8.241 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iHMIXWh" cx="0" cy="0" r="1" gradientTransform="rotate(-84.161 17.495 8.173)scale(2.35566 2.26902)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="o375d620d"/><stop offset="1" class="tgzndhrni"/></radialGradient><radialGradient id="iZFhrYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 20.687 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iqJUymd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 20.177 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iIfxIeM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 9.261 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iluDLDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 8.751 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ivjzpvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 21.707 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iwNBtlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 21.197 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iAyKCmx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 10.282 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="ireDgWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 9.772 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iN3ekpY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 22.727 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="i9czF6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 22.217 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iYIbosd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 11.302 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iBeQbPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 10.792 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iwVkT9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 23.748 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iqvKkkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 23.238 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ixyyVtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 12.322 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iUz1GON" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 11.812 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iqIlRze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 24.768 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iraNcty" cx="0" cy="0" r="1" gradientTransform="rotate(-97.511 23.055 1.525)scale(2.28523 2.20118)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="i8a7U2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.09374 -3.6172 12.35097 10.56365 9.4 23.59)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="tjsj1op7o"/><stop offset="1" class="gvudu0-9m"/></radialGradient><radialGradient id="iH7WSsc" cx="0" cy="0" r="1" gradientTransform="matrix(3.57813 0 0 3.06696 20.104 22.245)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="mqzky-b6t"/><stop offset="1" class="fnx367bbh"/></radialGradient><radialGradient id="iz3N9Og" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 1.30469 -.7272 -.3919 17.533 21.097)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="trt6sabjd"/><stop offset="1" class="s-qqz8oax"/></radialGradient><radialGradient id="iLmTvNj" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.29688 -4.54924 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="w9ewt285a"/><stop offset=".676" class="d7ua49w-t"/></radialGradient><radialGradient id="iWOFObc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.43739 -2.14179 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="hjenet4cg"/><stop offset="1" class="djivpvbhw"/></radialGradient><radialGradient id="iLnMLcb" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 3.017 16.73)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="ilMc2me" cx="0" cy="0" r="1" gradientTransform="rotate(130.522 5.587 5.085)scale(1.38839)" gradientUnits="userSpaceOnUse"><stop class="zi727lnsv"/><stop offset="1" class="z1e4imbuu"/></radialGradient><radialGradient id="iDgYjte" cx="0" cy="0" r="1" gradientTransform="matrix(.60938 -.49219 .26158 .32386 13.08 4.253)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="iOspXqd" cx="0" cy="0" r="1" gradientTransform="rotate(133.204 8.71 7.203)scale(1.58625 1.61077)" gradientUnits="userSpaceOnUse"><stop class="d0pq7p0hl"/><stop offset="1" class="kfhq2vx5n"/></radialGradient><radialGradient id="i6HCwxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.86008 .8467 0 19.227 7.23)" gradientUnits="userSpaceOnUse"><stop class="e6qjesbba"/><stop offset="1" class="btm953brw"/></radialGradient><radialGradient id="iHTVxLe" cx="0" cy="0" r="1" gradientTransform="rotate(128.601 8.882 6.9)scale(1.32441)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="iyq1_fb9e"/><stop offset="1" class="smjt6t9ha"/></radialGradient><radialGradient id="iprWAmd" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.54688 .29064 .30725 19.83 4.175)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="ia01BWX" cx="0" cy="0" r="1" gradientTransform="matrix(.7294 .35293 -.4289 .8864 9.106 9.349)" gradientUnits="userSpaceOnUse"><stop class="oughljbvw"/><stop offset="1" class="fm5egxmlo"/></radialGradient><radialGradient id="iNe5Amc" cx="0" cy="0" r="1" gradientTransform="matrix(.10577 -.86594 .53006 .06475 9.966 10.284)" gradientUnits="userSpaceOnUse"><stop class="ufab9bcqz"/><stop offset="1" class="rgangdc7y"/></radialGradient><radialGradient id="iPsaLGe" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 8.602 11.303)scale(1.55689 2.04215)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="i2r14vbib"/><stop offset="1" class="izxaz-bvs"/></radialGradient><radialGradient id="ijQY9Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.48626 -.41568 .26982 .31564 22.611 9.066)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ceu0gybff"/><stop offset="1" class="owp1j2bwg"/></radialGradient><radialGradient id="ip37IoS" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -1.046 22.855)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="itFCeSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.937 16.381)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="i5F8Rnb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.801 14.95)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iYYp79C" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5456 -8.733 0 16.549 10.915)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="a4xwf3bbh"/><stop offset=".978" class="sg1zpqbhq"/></radialGradient><radialGradient id="iuEj4hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.44 13.636)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="imccyNb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 13.713 -.03)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i9ATRgb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.426 15.937)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iPRLDTk" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.526 10.624)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="icXsFqc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.292 15.82)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="ii5waYd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.399 10.18)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="igipFGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.46 16.31)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="ihAG6pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.576 15.74)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iomKFWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.994 18.489)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iPdusZt" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.176 14.033)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ifjTTDb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.43 2.664)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUaGWGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.812 14.033)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ixqWmrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.526 14.252)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihMlInc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.611 14.047)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iDoM3hd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.972 14.592)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iT7PiAe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.086 14.764)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iEGSCde" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.468 11.51)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="itBKuEJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.08 14.69)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iq31Hcc" cx="0" cy="0" r="1" gradientTransform="rotate(99.989 6.91 11.148)scale(5.58466 4.97233)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fwcf4ds6u"/><stop offset="1" class="pg0l0_b5e"/></radialGradient><radialGradient id="iovwq8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31715 14 0 16.37 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="o_0wq7b5h"/><stop offset="1" class="nd4srkbik"/></radialGradient><radialGradient id="iSEn53b" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 2.5 -2.641 2.608 9.963 5.745)" gradientUnits="userSpaceOnUse"><stop class="vy-t95buc"/><stop offset="1" class="sy6a29bji"/></radialGradient><radialGradient id="iwwfhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73437 1.71095 -.24621 -.39349 22.549 5.206)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="zb7xzjb0z"/><stop offset="1" class="mvaqivyxk"/></radialGradient><radialGradient id="iF22uOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40552 1.24554 -1.0015 -.32607 22.679 5.72)" gradientUnits="userSpaceOnUse"><stop class="pldarnz2e"/><stop offset="1" class="sk_xim0ag"/></radialGradient><radialGradient id="i8z60vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 .96346 -.87532 -1.2526 15.68 9.806)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="rpngv328y"/><stop offset="1" class="t-rizvbci"/></radialGradient><radialGradient id="iDBZL0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 .5625 -.53002 -.60363 18.807 9.777)" gradientUnits="userSpaceOnUse"><stop class="xp17b02vv"/><stop offset="1" class="iu34ngpem"/></radialGradient><radialGradient id="iZDC2xd" cx="0" cy="0" r="1" gradientTransform="matrix(.63766 .79277 -.77436 .62286 13.053 9.777)" gradientUnits="userSpaceOnUse"><stop class="dp-wqtbjr"/><stop offset="1" class="b9skxcbce"/></radialGradient><radialGradient id="iaxQkid" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.0781 .32438 -.60175 11.697 6.214)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="sdopbqbnf"/><stop offset="1" class="bj8dg0b8l"/></radialGradient><radialGradient id="iCJwfdb" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 10.58 7.516)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="ixiw7Nc" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 23.257 4.851)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="i2Kf17d" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 3.836 4.541)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iyXQn0l" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 9.77 4.851)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwdleKr" cx="0" cy="0" r="1" gradientTransform="rotate(131.102 6.394 8.24)scale(2.51937 2.50772)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="oqfgbbi5b"/><stop offset="1" class="bvgzffjne"/></radialGradient><radialGradient id="iFovmgd" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 0 0 1.01563 14.557 9.495)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="r7-2wfbcc"/><stop offset="1" class="me2qedj2f"/></radialGradient><radialGradient id="ia6Q7le" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 -.67969 .45049 .56959 16.682 8.917)" gradientUnits="userSpaceOnUse"><stop class="mky8h2bzd"/><stop offset="1" class="dudenh09d"/></radialGradient><radialGradient id="iUCPwrb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.22 -1.443)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iC0wJeI" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 12.994 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iZfcJcb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 14.552 -4.775)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iubs2De" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 19.658 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="ifvdSwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06861 1.1704 -1.32316 -1.20809 16.615 2.453)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iHZGaVd" cx="0" cy="0" r="1" gradientTransform="matrix(.57433 -.42319 .25665 .34832 16.607 2.55)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwpylec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35276 -1.76557 0 15.994 2.496)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="smf6lpbrg"/><stop offset="1" class="h4ps77q_r"/></radialGradient><linearGradient id="iBGggtc" x1="8.354" x2="8.12" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wjgmmu2gq"/><stop offset="1" class="a7d2l_-4t"/></linearGradient><linearGradient id="iwSpWAe" x1="23.423" x2="24.011" y1="28.188" y2="28.188" gradientUnits="userSpaceOnUse"><stop class="aosu0gbmr"/><stop offset="1" class="p7fclrrnf"/></linearGradient><linearGradient id="iKpNxNi" x1="15.424" x2="15.658" y1="28.979" y2="28.979" gradientUnits="userSpaceOnUse"><stop class="utflpqb7a"/><stop offset="1" class="k0l9ze_pq"/></linearGradient><linearGradient id="i3SQbDe" x1="16.549" x2="16.283" y1="30.023" y2="30.023" gradientUnits="userSpaceOnUse"><stop offset=".368" class="cgi88gv2t"/><stop offset="1" class="ehqj11bbt"/></linearGradient><linearGradient id="iBCta6d" x1="7.913" x2="7.913" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iZHjg3d" x1="20.359" x2="20.359" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iB7870d" x1="19.601" x2="19.805" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="i0cYndb" x1="20.736" x2="20.58" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="iloAeIb" x1="8.933" x2="8.933" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i3YmUdc" x1="8.218" x2="8.367" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="irUks1b" x1="21.379" x2="21.379" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="i5Cpwir" x1="20.622" x2="20.825" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="irBmJac" x1="21.757" x2="21.6" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="iG44IVc" x1="9.953" x2="9.953" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="itK9dec" x1="9.239" x2="9.387" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iFaPctd" x1="22.399" x2="22.399" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iNOiLgd" x1="21.642" x2="21.846" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iXRpDRc" x1="22.777" x2="22.621" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="iNFHMKc" x1="10.974" x2="10.974" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iWwOBIc" x1="10.259" x2="10.407" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="idZzGvb" x1="23.42" x2="23.42" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iBIanRb" x1="22.662" x2="22.866" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iYF91vc" x1="23.797" x2="23.641" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ibWAHoB" x1="11.994" x2="11.994" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iNF4hvc" x1="11.279" x2="11.428" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="i0qGmeT" x1="24.44" x2="24.44" y1="24.792" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="imRqQGW" x1="23.683" x2="23.886" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iamWsYd" x1="24.338" x2="18.619" y1="21.261" y2="21.261" gradientUnits="userSpaceOnUse"><stop class="aw5v51m2w"/><stop offset="1" class="epa4jwbux"/></linearGradient><linearGradient id="iejUKqO" x1="18.213" x2="13.4" y1="22.839" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".388" class="xoq3wtioq"/><stop offset="1" class="shyqpdbhw"/></linearGradient><linearGradient id="iFbzqEd" x1="12.914" x2="12.914" y1="5.827" y2="7.839" gradientUnits="userSpaceOnUse"><stop class="hn2pq365w"/><stop offset="1" class="ckrbxabiw"/></linearGradient><linearGradient id="iYhr0Zc" x1="21.151" x2="16.798" y1="16.635" y2="16.635" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ir6pTOb" x1="16.041" x2="16.041" y1="21.201" y2="20.561" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iisl1Eb" x1="16.832" x2="15.994" y1="15.624" y2="15.659" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iuRhSNc" x1="15.994" x2="15.994" y1="16.764" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iwJJ10b" x1="15.994" x2="15.994" y1="13.809" y2="14.605" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iKzXIQN" x1="14.792" x2="15.11" y1="18.334" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iU5Kkqc" x1="18.954" x2="18.64" y1="14.087" y2="14.28" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikju3Mc" x1="14.556" x2="14.242" y1="14.087" y2="14.28" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZdHeme" x1="22.43" x2="21.223" y1="14.114" y2="16.29" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="igBNEkc" x1="10.144" x2="11.602" y1="14.818" y2="14.691" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iPVmwDe" x1="21.41" x2="21.41" y1="13.732" y2="15.636" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="igPCvHd" x1="15.791" x2="15.791" y1="12.347" y2="11.964" gradientUnits="userSpaceOnUse"><stop class="dfdb-obom"/><stop offset="1" class="ykc__8bxx"/></linearGradient><linearGradient id="izco7cb" x1="22.878" x2="22.213" y1="6.73" y2="6.652" gradientUnits="userSpaceOnUse"><stop class="lqxvkgj5w"/><stop offset="1" class="omim8hb6o"/></linearGradient><linearGradient id="iGnutIe" x1="19.362" x2="21.79" y1="7.448" y2="6.013" gradientUnits="userSpaceOnUse"><stop class="o_xhqbdfz"/><stop offset="1" class="cm4ghn5oa"/></linearGradient><linearGradient id="ixEacre" x1="16.422" x2="19.127" y1="7.073" y2="6.419" gradientUnits="userSpaceOnUse"><stop class="xgp1qchkh"/><stop offset="1" class="s3wqo851w"/></linearGradient><linearGradient id="iSbcJUc" x1="10.153" x2="12.446" y1="6.075" y2="7.817" gradientUnits="userSpaceOnUse"><stop class="xgzvgdboh"/><stop offset="1" class="a5j92oajv"/></linearGradient><filter id="iDpLQQd" width="6.055" height="2.589" x="6.611" y="23.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".375"/></filter><filter id="ikUYV5c" width="6.055" height="4.091" x="18.732" y="21.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".375"/></filter><filter id="iirk3Rb" width="1.02" height="3.045" x="7.221" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iQFOz3x" width="1.02" height="3.045" x="8.241" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iWkesTd" width="1.02" height="3.045" x="9.261" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iRYXdoe" width="1.02" height="3.045" x="10.282" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="ijjjync" width="1.02" height="3.045" x="11.302" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="ibUZJNc" width="6" height="2.728" x="7.08" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.686275 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.584314 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3520" result="effect2_innerShadow_13929_3520"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.521569 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_3520" result="effect3_innerShadow_13929_3520"/></filter><filter id="iQFSIOd" width="6" height="2.728" x="18.908" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.588235 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3520" result="effect2_innerShadow_13929_3520"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.709804 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_3520" result="effect3_innerShadow_13929_3520"/></filter><filter id="i6Sit9c" width="8.261" height="7.961" x="11.864" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3520" result="effect2_innerShadow_13929_3520"/></filter><filter id="iydwbUb" width="2.557" height="2.672" x="11.685" y="5.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iCga5yd" width="1.521" height="1.521" x="11.84" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.643137 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iulOqbc" width="2.416" height="2.353" x="17.968" y="5.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.717647 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iMk0Slc" width="1.521" height="1.521" x="18.629" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.572549 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="idy4Ucc" width="11.22" height="12.542" x="10.93" y="8.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3520" result="effect2_innerShadow_13929_3520"/></filter><filter id="iWRB15c" width="3.747" height="4.9" x="13.979" y="13.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".5"/></filter><filter id="iAsGSnd" width="2.277" height="3.3" x="14.855" y="13.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".1"/></filter><filter id="i7YHmEh" width="3.718" height="1.573" x="14.134" y="17.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".05"/></filter><filter id="iwFrbud" width=".787" height=".696" x="17.442" y="13.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".05"/></filter><filter id="iiSCjad" width=".891" height=".913" x="18.281" y="13.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".1"/></filter><filter id="iV8sSlj" width=".986" height="1.04" x="13.839" y="13.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".1"/></filter><filter id="iTaktuT" width=".913" height=".705" x="13.084" y="13.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".05"/></filter><filter id="ifddBxs" width="1.329" height="2.379" x="9.913" y="13.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".125"/></filter><filter id="iqNhqHe" width="1.947" height="2.903" x="20.437" y="13.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".25"/></filter><filter id="iF1u09b" width="1.535" height="1.535" x="21.971" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iU8EcFb" width="1.535" height="1.535" x="8.483" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="icNzjEc" width="2.656" height="2.656" x="14.668" y="8.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.443137 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="ijx6hcc" width="1.646" height="1.646" x="11.84" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="in9Rmyb" width="1.646" height="1.646" x="18.504" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter><filter id="iiwggqb" width="3.214" height="1.831" x="18.883" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".05"/></filter><filter id="igTFtXc" width="2.847" height="3.566" x="15.985" y="3.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".05"/></filter><filter id="ibjfADd" width="2.566" height="1.722" x="9.914" y="5.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3520" stdDeviation=".05"/></filter><filter id="inoPYoe" width="1.812" height="1.812" x="15.088" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3520"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-crown-dark" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a4xwf3bbh {
  stop-color: var(--svg-color--3d202f, #3D202F);
  stop-opacity: 0;
}

.a5j92oajv {
  stop-color: var(--svg-color--d99c45, #D99C45);
}

.a7d2l_-4t {
  stop-color: var(--svg-color--ff4c2c, #FF4C2C);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.aosu0gbmr {
  stop-color: var(--svg-color--ff4d0c, #FF4D0C);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.aw5v51m2w {
  stop-color: var(--svg-color--ffca34, #FFCA34);
}

.ay11wq5le {
  d: path("M16.549 29.964h-1.086v-6.281h1.086z");
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.azdozg41y {
  cx: 22.026px;
  cy: 9.419px;
  r: 0.817px;
}

.b9skxcbce {
  stop-color: var(--svg-color--e47a3c, #E47A3C);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc7d6obfi {
  stop-color: var(--svg-color--fda839, #FDA839);
}

.bj8dg0b8l {
  stop-color: var(--svg-color--e4ad53, #E4AD53);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.btm953brw {
  stop-color: var(--svg-color--c18731, #C18731);
  stop-opacity: 0;
}

.bvgzffjne {
  stop-color: var(--svg-color--377be9, #377BE9);
}

.c0g3mbbdp {
  d: path("M23.748 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.ceu0gybff {
  stop-color: var(--svg-color--59bfed, #59BFED);
}

.cgi88gv2t {
  stop-color: var(--svg-color--ffcf53, #FFCF53);
}

.ckrbxabiw {
  stop-color: var(--svg-color--efb863, #EFB863);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm4ghn5oa {
  stop-color: var(--svg-color--fbc46e, #FBC46E);
  stop-opacity: 0;
}

.cqs57sk5v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.135 3.808c.11.031.387.172.625.484c.237.313 1.38 1.985 1.922 2.781");
}

.d0pq7p0hl {
  stop-color: var(--svg-color--d9a439, #D9A439);
}

.d3e9_irck {
  d: path("M7.22 21.847h1.021v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.d7ua49w-t {
  stop-color: var(--svg-color--3e2027, #3E2027);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dfdb-obom {
  stop-color: var(--svg-color--ff7468, #FF7468);
}

.djivpvbhw {
  stop-color: var(--svg-color--2d1815, #2D1815);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dp-wqtbjr {
  stop-color: var(--svg-color--e47a3c, #E47A3C);
}

.dpitlhbpx {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
  stop-opacity: 0;
}

.dudenh09d {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6qjesbba {
  stop-color: var(--svg-color--c18731, #C18731);
}

.ehqj11bbt {
  stop-color: var(--svg-color--fc4, #FC4);
  stop-opacity: 0;
}

.eif22vbdr {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
  stop-opacity: 0;
}

.ekzgfq9bb {
  d: path("M10.908 13.75a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.epa4jwbux {
  stop-color: var(--svg-color--ffbc10, #FFBC10);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.escp53_pi {
  d: path("M11.302 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.ewitywhfr {
  cx: 9.966px;
  cy: 9.419px;
  r: 0.817px;
}

.f-t10ph2f {
  cx: 17.494px;
  cy: 25.261px;
  r: 0.547px;
}

.f19u2wb6f {
  cx: 12.601px;
  cy: 4.609px;
  r: 0.761px;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f8xv78wwh {
  d: path("M19.667 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fiwhz1yao {
  stop-color: var(--svg-color--fad771, #FAD771);
  stop-opacity: 0;
}

.fj7de7bxl {
  d: path("M18.112 13.745c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.39-.05");
}

.fm5egxmlo {
  stop-color: var(--svg-color--267ebb, #267EBB);
}

.fnx367bbh {
  stop-color: var(--svg-color--ffcc36, #FFCC36);
  stop-opacity: 0;
}

.fsr110b8t {
  stop-color: var(--svg-color--ff6a30, #FF6A30);
}

.ft5dv1b6b {
  fill: none;
}

.fw-_ge0oq {
  d: path("M7.08 20.972a1 1 0 0 1 1-1h5v2.578h-5.2a.8.8 0 0 1-.8-.8z");
}

.fwcf4ds6u {
  stop-color: var(--svg-color--f2b056, #F2B056);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g5wpc5oah {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.385 13.284c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.gaqflu3bm {
  d: path("m9.11 5.009l1.287 7.093a.25.25 0 0 0 .246.205h10.702a.25.25 0 0 0 .246-.205l1.287-7.093l-3.37 2.107a.495.495 0 0 1-.666-.13l-.666-.946c-.551-.784-1.11-1.58-1.371-1.89c-.38-.454-.651-.476-.807-.477h-.007c-.156 0-.427.023-.808.477c-.26.31-.82 1.106-1.37 1.89c-.232.33-.462.657-.667.946a.495.495 0 0 1-.667.13z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gvudu0-9m {
  stop-color: var(--svg-color--c37b21, #C37B21);
}

.h_mah-buv {
  stop-color: var(--svg-color--fad771, #FAD771);
}

.h4ps77q_r {
  stop-color: var(--svg-color--d89b45, #D89B45);
}

.hjenet4cg {
  stop-color: var(--svg-color--2d1815, #2D1815);
  stop-opacity: 0;
}

.hn2pq365w {
  stop-color: var(--svg-color--f6c164, #F6C164);
}

.i2r14vbib {
  stop-color: var(--svg-color--39b6de, #39B6DE);
}

.i3n99zbcs {
  fill: var(--svg-color--fb3310, #FB3310);
  d: path("M24.037 23.89h-.911v.82c0 .149.12.269.268.269h.375c.148 0 .268-.12.268-.268z");
}

.i5vxhhb9k {
  cx: 15.994px;
  cy: 20.519px;
  rx: 2.32px;
  ry: 2.297px;
}

.i6zt6f36k {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.603 13.284c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.ipe5nqbjx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.112 13.745c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.136.39-.05");
}

.iu34ngpem {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
  stop-opacity: 0;
}

.iyq1_fb9e {
  stop-color: var(--svg-color--e4bb48, #E4BB48);
}

.izxaz-bvs {
  stop-color: var(--svg-color--3c7dcd, #3C7DCD);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j0k3id93s {
  stop-color: var(--svg-color--984900, #984900);
  stop-opacity: 0;
}

.j0o8lia9p {
  d: path("M11.169 17.714a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.69.239 5.556");
}

.j8vxk9r3t {
  fill: var(--svg-color--e12706, #E12706);
  d: path("M11.916 23.904h-.911v.82c0 .149.12.269.268.269h.375c.148 0 .268-.12.268-.268z");
}

.j9g9dbhkm {
  d: path("M12.65 5.167c-.468.188-.824 1.206-.965 1.649l1.16 1.023l1.298-.96c-.801-1.454-1.149-1.638-1.297-1.68z");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jk0mh1bxi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 7.269c.07.08.261.226.461.164c.2-.063 1.719-1.037 2.453-1.516");
}

.jnpel9bup {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
}

.jo4sxnm8i {
  stop-color: var(--svg-color--e0613c, #E0613C);
}

.jrd3jzgth {
  stop-color: var(--svg-color--dd7423, #DD7423);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jzfasvbbp {
  cx: 22.739px;
  cy: 5.184px;
  r: 0.767px;
}

.k0l9ze_pq {
  stop-color: var(--svg-color--da7c13, #DA7C13);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k8wj80bfs {
  cx: 13.54px;
  cy: 13.937px;
  rx: 0.39px;
  ry: 0.197px;
}

.kbcpr6bot {
  d: path("M22.727 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.kfayvkisl {
  cx: 17.494px;
  cy: 28.386px;
  r: 0.547px;
}

.kfhq2vx5n {
  stop-color: var(--svg-color--c68e33, #C68E33);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kiolp_-pe {
  d: path("M21.707 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.kowfi484h {
  cx: 15.994px;
  cy: 2.942px;
  r: 0.906px;
}

.kz6jvgbzd {
  stop-color: var(--svg-color--e0a155, #E0A155);
}

.l0yglmb3r {
  stop-color: var(--svg-color--e5c652, #E5C652);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l2jyntb4f {
  stop-color: var(--svg-color--ffad23, #FFAD23);
}

.ldyj_nb1e {
  cx: 9.25px;
  cy: 5.184px;
  r: 0.767px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lll2sghve {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m10.065 5.863l2.265 1.421");
}

.lqxvkgj5w {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
}

.ltsxllb3q {
  stop-color: var(--svg-color--d37902, #D37902);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m3xuw6x7t {
  fill: var(--svg-color--e12706, #E12706);
  d: path("M7.361 23.904h1.822v.82c0 .149-.12.269-.268.269H8.54a.27.27 0 0 1-.268-.265a.27.27 0 0 1-.268.265H7.63a.27.27 0 0 1-.268-.268zm1.822 0v.82c0 .149.12.269.268.269h.375a.27.27 0 0 0 .268-.265a.27.27 0 0 0 .268.265h.375c.148 0 .268-.12.268-.268v-.82z");
}

.m8_9xackt {
  stop-color: var(--svg-color--e7175a, #E7175A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me2qedj2f {
  stop-color: var(--svg-color--467ec1, #467EC1);
  stop-opacity: 0;
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mky8h2bzd {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
}

.mqzky-b6t {
  stop-color: var(--svg-color--ffcc36, #FFCC36);
}

.mvaqivyxk {
  stop-color: var(--svg-color--cd9d50, #CD9D50);
  stop-opacity: 0;
}

.mx5qf9bzw {
  stop-color: var(--svg-color--ffab48, #FFAB48);
}

.n4msb7ugs {
  cx: 12.663px;
  cy: 9.409px;
  r: 0.823px;
}

.n5q_2-c9z {
  cx: 13.54px;
  cy: 13.937px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ncr9djbkt {
  fill: var(--svg-color--fb3310, #FB3310);
  d: path("M19.482 22.388h1.822v2.323c0 .148-.12.268-.268.268h-.375a.27.27 0 0 1-.268-.265a.27.27 0 0 1-.268.265h-.375a.27.27 0 0 1-.268-.268zm1.822 0v2.323c0 .148.12.268.268.268h.375a.27.27 0 0 0 .268-.265a.27.27 0 0 0 .268.265h.375c.148 0 .268-.12.268-.268v-.821z");
}

.nd4srkbik {
  stop-color: var(--svg-color--fa865b, #FA865B);
  stop-opacity: 0;
}

.o_0wq7b5h {
  stop-color: var(--svg-color--fa865b, #FA865B);
}

.o_4gny8-z {
  stop-color: var(--svg-color--dd7423, #DD7423);
}

.o_xhqbdfz {
  stop-color: var(--svg-color--fbc46e, #FBC46E);
}

.o-695ij2e {
  stop-color: var(--svg-color--984900, #984900);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o375d620d {
  stop-color: var(--svg-color--e08711, #E08711);
  stop-opacity: 0;
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omim8hb6o {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
  stop-opacity: 0;
}

.oqfgbbi5b {
  stop-color: var(--svg-color--26a4db, #26A4DB);
}

.oughljbvw {
  stop-color: var(--svg-color--3f8dc5, #3F8DC5);
}

.owp1j2bwg {
  stop-color: var(--svg-color--59bfed, #59BFED);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p691-zb3j {
  d: path("M14.625 14.344c0-.289-.234-.481-.298-.54l-.288.28l.177.361z");
}

.p7fclrrnf {
  stop-color: var(--svg-color--ff4d0c, #FF4D0C);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pd-kjcckg {
  stop-color: var(--svg-color--ffc95d, #FFC95D);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pg0l0_b5e {
  stop-color: var(--svg-color--e3964c, #E3964C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pldarnz2e {
  stop-color: var(--svg-color--d79e4a, #D79E4A);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pxse0-u4m {
  cx: 19.327px;
  cy: 9.409px;
  r: 0.823px;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q5a0_7mqo {
  stop-color: var(--svg-color--ff6e46, #FF6E46);
}

.q8zps5bkz {
  fill: var(--svg-color--ffbf46, #FFBF46);
  d: path("M16.549 29.964h-1.086v-6.281h1.086z");
}

.qk8v1bc2n {
  cx: 19.39px;
  cy: 4.609px;
  r: 0.761px;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r7-2wfbcc {
  stop-color: var(--svg-color--467ec1, #467EC1);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rez3ddccp {
  stop-color: var(--svg-color--e5780c, #E5780C);
}

.rgangdc7y {
  stop-color: var(--svg-color--416ec4, #416EC4);
  stop-opacity: 0;
}

.rnq8zfbyk {
  d: path("M9.261 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.rpngv328y {
  stop-color: var(--svg-color--e1754f, #E1754F);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rrwvrg1ho {
  stop-color: var(--svg-color--ff6e46, #FF6E46);
  stop-opacity: 0;
}

.ryyd73bhi {
  d: path("M18.178 13.556a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.s-qqz8oax {
  stop-color: var(--svg-color--e68600, #E68600);
  stop-opacity: 0;
}

.s3wqo851w {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
  stop-opacity: 0;
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sblhzud6f {
  stop-color: var(--svg-color--e11f40, #E11F40);
}

.sdopbqbnf {
  stop-color: var(--svg-color--e4ad53, #E4AD53);
}

.sg1zpqbhq {
  stop-color: var(--svg-color--34151a, #34151A);
}

.sgtr8ibeb {
  d: path("M24.908 20.972a1 1 0 0 0-1-1h-5v2.578h5.2a.8.8 0 0 0 .8-.8z");
}

.shgrjqbiz {
  d: path("M20.687 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.shyqpdbhw {
  stop-color: var(--svg-color--d88f1c, #D88F1C);
}

.sk_xim0ag {
  stop-color: var(--svg-color--d79e4a, #D79E4A);
  stop-opacity: 0;
}

.smf6lpbrg {
  stop-color: var(--svg-color--d89b45, #D89B45);
  stop-opacity: 0;
}

.smjt6t9ha {
  stop-color: var(--svg-color--d2961e, #D2961E);
}

.sv01lobuk {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.592 14.43l-.59 1.839c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.408-.505-.408-.616 0");
}

.swjgceb9v {
  d: path("M10.282 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.sy6a29bji {
  stop-color: var(--svg-color--dda44f, #DDA44F);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t-rizvbci {
  stop-color: var(--svg-color--e1754f, #E1754F);
  stop-opacity: 0;
}

.t0v0fubzw {
  d: path("M20.855 16.2a1.63 1.63 0 0 0 .904-.31v.932c0 .893-.532 1.689-1.34 2.019q.256-.546.346-1.18z");
}

.t3kcpjbyb {
  cx: 15.996px;
  cy: 9.409px;
  r: 1.328px;
}

.t4qznn7ln {
  d: path("M10.94 13.09a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.tgzndhrni {
  stop-color: var(--svg-color--ae5301, #AE5301);
}

.tjsj1op7o {
  stop-color: var(--svg-color--dda72d, #DDA72D);
}

.trt6sabjd {
  stop-color: var(--svg-color--e68600, #E68600);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u_7404bbu {
  stop-color: var(--svg-color--ff834e, #FF834E);
}

.u_l38sbak {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 14.448a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u8ozf6b8x {
  stop-color: var(--svg-color--e5780c, #E5780C);
  stop-opacity: 0;
}

.ufab9bcqz {
  stop-color: var(--svg-color--416ec4, #416EC4);
}

.us1u98b3g {
  d: path("M23.635 22.456c2.514 2.141 3.575 5.222 4.027 7.508h-4.027z");
}

.utflpqb7a {
  stop-color: var(--svg-color--da7c13, #DA7C13);
}

.uuabbt8jv {
  d: path("M20.937 15.636q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.v1k_mhzfg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v4gg9p-ym {
  stop-color: var(--svg-color--ff8258, #FF8258);
}

.v65_ahc-c {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.643 17.451a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.002c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.vmhbtsb-a {
  d: path("M8.241 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.vsg8c7gji {
  stop-color: var(--svg-color--ff432e, #FF432E);
}

.vuv5a3b-t {
  d: path("M18.973 14.331a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.vy-t95buc {
  stop-color: var(--svg-color--dda44f, #DDA44F);
}

.w_324qbof {
  stop-color: var(--svg-color--fff150, #FFF150);
}

.w_ld-kbgg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w9ewt285a {
  stop-color: var(--svg-color--341b29, #341B29);
}

.we5kvqbpm {
  cx: 15.994px;
  cy: 20.206px;
  r: 3.98px;
}

.wjgmmu2gq {
  stop-color: var(--svg-color--ff4c2c, #FF4C2C);
}

.ww_ne9n0y {
  d: path("M20.916 16.29c.065-1.064.129-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x9knvh_3c {
  stop-color: var(--svg-color--ff5730, #FF5730);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xgp1qchkh {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
}

.xgzvgdboh {
  stop-color: var(--svg-color--e4aa42, #E4AA42);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xmc2l2-sl {
  stop-color: var(--svg-color--ffc95d, #FFC95D);
}

.xoq3wtioq {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
}

.xp17b02vv {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
}

.xt4ezwz_m {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.612 14.235l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.y6o_a1bwr {
  d: path("M13.81 13.556a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.ydfb--rgm {
  d: path("M11.133 16.2a1.64 1.64 0 0 1-.905-.31v.932c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.ykc__8bxx {
  stop-color: var(--svg-color--ff865b, #FF865B);
  stop-opacity: 0;
}

.yn34xubbb {
  d: path("m15.612 14.235l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.yq4cmdu2g {
  d: path("M4.338 29.964c.766-3.875 3.281-10.031 11.656-10.031v.037l.012-.037c8.375 0 10.89 6.156 11.656 10.031z");
}

.z01xu_6ui {
  d: path("M15.994 17.846c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.z0o3egbpm {
  fill: var(--svg-color--000, #000);
  d: path("M17.667 14.448c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.z1e4imbuu {
  stop-color: var(--svg-color--e2aa40, #E2AA40);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z9ftlqvnr {
  d: path("M8.354 22.466c-2.507 2.14-3.565 5.215-4.016 7.498h4.016z");
}

.zb7wmmorx {
  d: path("M19.15 5.218c-.362.134-.868.96-1.082 1.316l.664 1.012l1.653-.535c-.43-1.27-.782-1.961-1.235-1.793");
}

.zb7xzjb0z {
  stop-color: var(--svg-color--cd9d50, #CD9D50);
}

.zi727lnsv {
  stop-color: var(--svg-color--f1c752, #F1C752);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zl0i2nl5t {
  stop-color: var(--svg-color--fca135, #FCA135);
}

.zupcoccwr {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
