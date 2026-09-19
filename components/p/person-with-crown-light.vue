<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBYqcqb)" class="hgknd0bcu"/><path fill="url(#iP6PLfc)" class="hgknd0bcu"/><path fill="url(#iQIno6d)" class="z9ftlqvnr"/><path fill="url(#iBGggtc)" class="z9ftlqvnr"/><path fill="url(#iMyPqOK)" class="us1u98b3g"/><path fill="url(#iwSpWAe)" class="us1u98b3g"/><g filter="url(#iFGqjOd)"><path class="m3xuw6x7t"/><path class="j8vxk9r3t"/></g><g filter="url(#iQg26Db)"><path class="ncr9djbkt"/><path class="i3n99zbcs"/></g><path class="ll-sfjbvs"/><path fill="url(#iKpNxNi)" class="jxiqgfbai"/><path fill="url(#iAjKzvn)" class="jxiqgfbai"/><path fill="url(#iyxEWTc)" class="jxiqgfbai"/><circle fill="url(#it7yh0c)" class="kfayvkisl"/><g filter="url(#ircbAOd)"><path fill="url(#igYMrNc)" class="qq1243s9v"/><path fill="url(#isSgzqc)" class="qq1243s9v"/><path fill="url(#iHMIXWh)" class="qq1243s9v"/></g><path fill="url(#i8OHdZL)" class="taakstd9a"/><path fill="url(#iB7870d)" class="taakstd9a"/><path fill="url(#iaKbtNc)" class="taakstd9a"/><path fill="url(#i0cYndb)" class="taakstd9a"/><path fill="url(#ihiiZQd)" class="taakstd9a"/><g filter="url(#iMVRLrd)"><path fill="url(#ihZ8ljd)" class="cm2ynzezx"/><path fill="url(#iUhay3c)" class="cm2ynzezx"/><path fill="url(#i8Xb03d)" class="cm2ynzezx"/><path fill="url(#i3YmUdc)" class="cm2ynzezx"/></g><path fill="url(#ix94lod)" class="d-y7wjh4h"/><path fill="url(#i5Cpwir)" class="d-y7wjh4h"/><path fill="url(#i245Ttc)" class="d-y7wjh4h"/><path fill="url(#irBmJac)" class="d-y7wjh4h"/><path fill="url(#i6qQ5Rc)" class="d-y7wjh4h"/><g filter="url(#iAjjYud)"><path fill="url(#irrycLb)" class="xmck5lbbx"/><path fill="url(#iK6joVd)" class="xmck5lbbx"/><path fill="url(#iNIDrTc)" class="xmck5lbbx"/><path fill="url(#itK9dec)" class="xmck5lbbx"/></g><path fill="url(#iO03fwe)" class="kkaqah18a"/><path fill="url(#iNOiLgd)" class="kkaqah18a"/><path fill="url(#iZbYshd)" class="kkaqah18a"/><path fill="url(#iXRpDRc)" class="kkaqah18a"/><path fill="url(#iC5NJqb)" class="kkaqah18a"/><g filter="url(#iRzIFUb)"><path fill="url(#i7kl0Ed)" class="dvti4ibqx"/><path fill="url(#ipVE1Ld)" class="dvti4ibqx"/><path fill="url(#i9w1QPe)" class="dvti4ibqx"/><path fill="url(#iWwOBIc)" class="dvti4ibqx"/></g><path fill="url(#iewIeqd)" class="temm9m1gz"/><path fill="url(#iBIanRb)" class="temm9m1gz"/><path fill="url(#icp8dXb)" class="temm9m1gz"/><path fill="url(#iYF91vc)" class="temm9m1gz"/><path fill="url(#iiBx4xd)" class="temm9m1gz"/><g filter="url(#i71w48b)"><path fill="url(#il892Jq)" class="y78x6obne"/><path fill="url(#idvDDwc)" class="y78x6obne"/><path fill="url(#i7168zb)" class="y78x6obne"/><path fill="url(#iNF4hvc)" class="y78x6obne"/></g><path fill="url(#i4uy3yd)" class="ii6c7s39l"/><path fill="url(#imRqQGW)" class="ii6c7s39l"/><path fill="url(#iBr2Iyd)" class="ii6c7s39l"/><path fill="url(#iraNcty)" class="ii6c7s39l"/><g filter="url(#ieOPRwe)"><path fill="url(#i8a7U2b)" class="s8wgbib2e"/></g><g filter="url(#iGBCbKb)"><path fill="url(#iamWsYd)" class="k_vmfilmc"/><path fill="url(#iH7WSsc)" class="k_vmfilmc"/></g><g filter="url(#i0Bseec)"><circle fill="url(#iKHOimb)" class="we5kvqbpm"/><circle fill="url(#iaowRfb)" class="we5kvqbpm"/></g><ellipse fill="url(#iek0PKI)" class="o297js0_g"/><ellipse fill="url(#iDdjmrb)" class="o297js0_g"/><circle fill="url(#iyXNDUc)" class="f-t10ph2f"/><g filter="url(#iQ0sKWc)"><path fill="url(#ixusqle)" class="fcxmlvlbk"/></g><g filter="url(#il0uZ0d)"><circle fill="url(#ilMc2me)" class="f19u2wb6f"/><circle fill="url(#iDgYjte)" class="f19u2wb6f"/></g><g filter="url(#iq0g8sd)"><path fill="url(#iOspXqd)" class="zb7wmmorx"/><path fill="url(#i6HCwxb)" class="zb7wmmorx"/></g><g filter="url(#iltI0sI)"><circle fill="url(#iHTVxLe)" class="qk8v1bc2n"/><circle fill="url(#iprWAmd)" class="qk8v1bc2n"/></g><circle fill="url(#iERdJId)" class="v-aq_fb5e"/><circle fill="url(#iNe5Amc)" class="v-aq_fb5e"/><circle fill="url(#iYc4gLe)" class="prxm8ubjj"/><circle fill="url(#ijQY9Cb)" class="prxm8ubjj"/><path fill="url(#i5newJe)" class="lhbsumjnz"/><path fill="url(#i7HJuMJ)" class="vsszmllkn"/><g filter="url(#inKYGDe)"><path fill="url(#isuSrWc)" class="jpa7s1h3a"/></g><path fill="url(#iHySmhe)" class="jpa7s1h3a"/><path fill="url(#iYg5nrd)" class="jpa7s1h3a"/><path fill="url(#it5PJ5d)" class="jpa7s1h3a"/><path fill="url(#izKjI1a)" class="jpa7s1h3a"/><path fill="url(#iVL7o0c)" class="jpa7s1h3a"/><path fill="url(#i90z42b)" class="jpa7s1h3a"/><path fill="url(#ieVfxDc)" class="jpa7s1h3a"/><g filter="url(#iAEeKTT)"><path class="p6e0x9tlj"/></g><g filter="url(#iPSgN0b)"><path class="kh0u3slld"/><path fill="url(#iATyoGd)" class="r5r21mbtx"/><path fill="url(#itNcTmb)" class="r5r21mbtx"/><path fill="url(#idLKUTd)" class="r5r21mbtx"/><path fill="url(#i2H0aqc)" class="r5r21mbtx"/><path fill="url(#i09yf1b)" class="r5r21mbtx"/></g><g filter="url(#iR4gdNb)"><path stroke="url(#icxDjEc)" class="ut-12mb9a"/></g><path fill="url(#i9e0hUf)" class="odv1wqwrs"/><path class="yp_h4cxpw"/><path fill="url(#iptEtAe)" class="uy_ysvgeb"/><path class="utmko7bie"/><g filter="url(#iYEWDTb)"><path class="s20fc4arp"/><path fill="url(#iE4LFbd)" class="e1zap2b6k"/></g><g filter="url(#i88Dbze)"><path fill="url(#i5WTTwe)" class="xrm2prbkt"/></g><path class="ucl97ybiq"/><path fill="url(#iGX9r0v)" class="n2y_l5h3h"/><path class="z2x1q0bwg"/><g filter="url(#iaQRyfe)"><path fill="url(#iAedIEc)" class="shnlphbde"/></g><g filter="url(#iv5Uxab)"><ellipse transform="rotate(-27.914 13.54 13.917)" class="bm954bbaf"/><ellipse fill="url(#iQng2ac)" transform="rotate(-27.914 13.54 13.917)" class="x-hxw-bgc"/></g><path fill="url(#i3TFEXJ)" class="n5f-q5igg"/><path fill="url(#iUGwhze)" class="n5f-q5igg"/><path fill="url(#iDv2Eoe)" class="n5f-q5igg"/><path fill="url(#iL5bI8v)" class="n5f-q5igg"/><path fill="url(#iGQA5kL)" class="p80wfibmc"/><path fill="url(#i9WsZTt)" class="p80wfibmc"/><g filter="url(#ipzsiHB)"><path fill="url(#iTCrs2d)" class="iwcw2ibei"/></g><g filter="url(#iBAbMne)"><path fill="url(#iKD7bzd)" class="rwrql1b8d"/></g><path fill="url(#iq31Hcc)" class="pwdyrab-n"/><path fill="url(#iovwq8b)" class="pwdyrab-n"/><path fill="url(#igPCvHd)" class="pwdyrab-n"/><path fill="url(#iSEn53b)" class="pwdyrab-n"/><path fill="url(#iwwfhfb)" class="pwdyrab-n"/><path fill="url(#imKujHe)" class="pwdyrab-n"/><path fill="url(#ilSsPFd)" class="pwdyrab-n"/><path fill="url(#i8z60vd)" class="pwdyrab-n"/><path fill="url(#irCHEVn)" class="pwdyrab-n"/><path fill="url(#iAuTJ6b)" class="pwdyrab-n"/><path fill="url(#iaxQkid)" class="pwdyrab-n"/><g filter="url(#im2Xkwe)"><circle fill="url(#iCJwfdb)" class="jzfasvbbp"/><circle fill="url(#ixiw7Nc)" class="jzfasvbbp"/></g><g filter="url(#il5BUle)"><circle fill="url(#i2Kf17d)" class="ldyj_nb1e"/><circle fill="url(#iyXQn0l)" class="ldyj_nb1e"/></g><g filter="url(#i7uTfLc)"><circle fill="url(#iwdleKr)" class="t3kcpjbyb"/><circle fill="url(#iFovmgd)" class="t3kcpjbyb"/><circle fill="url(#ia6Q7le)" class="t3kcpjbyb"/></g><g filter="url(#i8QulQc)"><circle fill="url(#iUCPwrb)" class="n4msb7ugs"/><circle fill="url(#icYySuN)" class="n4msb7ugs"/></g><g filter="url(#iDmsswc)"><circle fill="url(#iZfcJcb)" class="pxse0-u4m"/><circle fill="url(#iHUahhe)" class="pxse0-u4m"/></g><g filter="url(#iREq0Yd)"><path stroke="url(#iGnutIe)" class="l7-dtlm-e"/></g><g filter="url(#iNhNJtW)"><path stroke="url(#iBURqYd)" class="xslzggb2v"/></g><g filter="url(#iX5BYSc)"><path stroke="url(#iJAl6YN)" class="x36tsjbay"/></g><g filter="url(#iF9sWvd)"><circle fill="url(#ifvdSwb)" class="kowfi484h"/><circle fill="url(#iHZGaVd)" class="kowfi484h"/></g><circle fill="url(#iwpylec)" class="kowfi484h"/><defs><radialGradient id="iBYqcqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.5625 -14.1309 0 16 22.401)" gradientUnits="userSpaceOnUse"><stop class="vsg8c7gji"/><stop offset=".542" class="x9knvh_3c"/></radialGradient><radialGradient id="iP6PLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9375 0 0 -23.6312 23.807 29.964)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="q5a0_7mqo"/><stop offset="1" class="rrwvrg1ho"/></radialGradient><radialGradient id="iQIno6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.28332 4.28735 0 8.354 29.67)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="fsr110b8t"/><stop offset="1" class="jo4sxnm8i"/></radialGradient><radialGradient id="iMyPqOK" cx="0" cy="0" r="1" gradientTransform="matrix(3.36005 0 0 6.32267 23.847 28.93)" gradientUnits="userSpaceOnUse"><stop class="u_7404bbu"/><stop offset="1" class="v4gg9p-ym"/></radialGradient><radialGradient id="iyxEWTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .69531 -2.16649 0 16.006 23.956)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="o_4gny8-z"/><stop offset=".622" class="jrd3jzgth"/></radialGradient><radialGradient id="it7yh0c" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 2.282 18.29)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="isSgzqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 8.241 24.565)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iHMIXWh" cx="0" cy="0" r="1" gradientTransform="rotate(-84.161 17.495 8.173)scale(2.35566 2.26902)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="o375d620d"/><stop offset="1" class="tgzndhrni"/></radialGradient><radialGradient id="iaKbtNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 20.687 24.565)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="ihiiZQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 20.177 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="o375d620d"/><stop offset=".957" class="tgzndhrni"/></radialGradient><radialGradient id="iUhay3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 9.261 24.565)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="i8Xb03d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 8.751 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="i245Ttc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 21.707 24.565)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="i6qQ5Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 21.197 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="o375d620d"/><stop offset=".957" class="tgzndhrni"/></radialGradient><radialGradient id="iK6joVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 10.282 24.565)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iNIDrTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 9.772 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iZbYshd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 22.727 24.565)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iC5NJqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 22.217 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="o375d620d"/><stop offset=".957" class="tgzndhrni"/></radialGradient><radialGradient id="ipVE1Ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 11.302 24.565)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="i9w1QPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 10.792 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="icp8dXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 23.748 24.565)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iiBx4xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 23.238 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="o375d620d"/><stop offset=".957" class="tgzndhrni"/></radialGradient><radialGradient id="idvDDwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 12.322 24.565)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="i7168zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 11.812 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iBr2Iyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 24.768 24.565)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iraNcty" cx="0" cy="0" r="1" gradientTransform="rotate(-97.511 23.055 1.525)scale(2.28523 2.20118)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="i8a7U2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.09374 -3.6172 12.35097 10.56365 9.4 23.59)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="tjsj1op7o"/><stop offset="1" class="gvudu0-9m"/></radialGradient><radialGradient id="iH7WSsc" cx="0" cy="0" r="1" gradientTransform="matrix(3.57813 0 0 3.06696 20.104 22.245)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="mqzky-b6t"/><stop offset="1" class="fnx367bbh"/></radialGradient><radialGradient id="iaowRfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 1.30469 -.7272 -.3919 17.533 21.096)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="trt6sabjd"/><stop offset="1" class="s-qqz8oax"/></radialGradient><radialGradient id="iek0PKI" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.29688 -4.54924 0 15.994 20.518)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ql1-3v45r"/><stop offset=".676" class="r84slnqkj"/></radialGradient><radialGradient id="iDdjmrb" cx="0" cy="0" r="1" gradientTransform="matrix(2.90154 0 0 2.93114 15.413 20.518)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="o4kt6qgcl"/><stop offset=".976" class="jdm59-bck"/></radialGradient><radialGradient id="iyXNDUc" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 3.017 16.729)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="ilMc2me" cx="0" cy="0" r="1" gradientTransform="rotate(130.522 5.587 5.085)scale(1.38839)" gradientUnits="userSpaceOnUse"><stop class="zi727lnsv"/><stop offset="1" class="z1e4imbuu"/></radialGradient><radialGradient id="iDgYjte" cx="0" cy="0" r="1" gradientTransform="matrix(.60938 -.49219 .26158 .32386 13.08 4.253)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="iOspXqd" cx="0" cy="0" r="1" gradientTransform="rotate(133.204 8.71 7.203)scale(1.58625 1.61077)" gradientUnits="userSpaceOnUse"><stop class="d0pq7p0hl"/><stop offset="1" class="kfhq2vx5n"/></radialGradient><radialGradient id="i6HCwxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.86008 .8467 0 19.227 7.23)" gradientUnits="userSpaceOnUse"><stop class="e6qjesbba"/><stop offset="1" class="btm953brw"/></radialGradient><radialGradient id="iHTVxLe" cx="0" cy="0" r="1" gradientTransform="rotate(128.601 8.882 6.9)scale(1.32441)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="iyq1_fb9e"/><stop offset="1" class="smjt6t9ha"/></radialGradient><radialGradient id="iprWAmd" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.54688 .29064 .30725 19.83 4.175)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="iERdJId" cx="0" cy="0" r="1" gradientTransform="matrix(.7294 .35293 -.4289 .8864 9.106 9.348)" gradientUnits="userSpaceOnUse"><stop class="oughljbvw"/><stop offset="1" class="fm5egxmlo"/></radialGradient><radialGradient id="iNe5Amc" cx="0" cy="0" r="1" gradientTransform="matrix(.10577 -.86594 .53006 .06475 9.966 10.284)" gradientUnits="userSpaceOnUse"><stop class="ufab9bcqz"/><stop offset="1" class="rgangdc7y"/></radialGradient><radialGradient id="iYc4gLe" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 8.602 11.302)scale(1.55689 2.04215)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="i2r14vbib"/><stop offset="1" class="izxaz-bvs"/></radialGradient><radialGradient id="ijQY9Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.48626 -.41568 .26982 .31564 22.611 9.066)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ceu0gybff"/><stop offset="1" class="owp1j2bwg"/></radialGradient><radialGradient id="i5newJe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -1.031 22.845)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i7HJuMJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.937 16.36)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="isuSrWc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.801 14.928)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iYg5nrd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59374 12.4375 -10.29978 -1.31982 17.988 9.59)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="nt6io9bbg"/><stop offset="1" class="b3ssyu2ir"/></radialGradient><radialGradient id="it5PJ5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.44 13.616)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="izKjI1a" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.694 13.662)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iVL7o0c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.427 15.916)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="i90z42b" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 10.526 10.603)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ieVfxDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.42 9.95)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="itNcTmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.46 16.29)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i2H0aqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.576 15.72)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="i9e0hUf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.994 18.468)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iptEtAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.176 14.013)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iE4LFbd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.426 2.653)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGX9r0v" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.812 14.013)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iQng2ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.526 14.231)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUGwhze" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.611 14.027)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iDv2Eoe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.972 14.572)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iL5bI8v" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.086 14.744)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="i9WsZTt" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.985 6.998)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iTCrs2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 11.08 14.67)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iq31Hcc" cx="0" cy="0" r="1" gradientTransform="rotate(99.989 6.91 11.148)scale(5.58466 4.97233)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fwcf4ds6u"/><stop offset="1" class="pg0l0_b5e"/></radialGradient><radialGradient id="iovwq8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31715 14 0 16.37 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="o_0wq7b5h"/><stop offset="1" class="nd4srkbik"/></radialGradient><radialGradient id="iSEn53b" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 2.5 -2.641 2.608 9.963 5.745)" gradientUnits="userSpaceOnUse"><stop class="vy-t95buc"/><stop offset="1" class="sy6a29bji"/></radialGradient><radialGradient id="iwwfhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73437 1.71095 -.24621 -.39349 22.549 5.206)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="zb7xzjb0z"/><stop offset="1" class="mvaqivyxk"/></radialGradient><radialGradient id="imKujHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40552 1.24554 -1.0015 -.32607 22.679 5.719)" gradientUnits="userSpaceOnUse"><stop class="pldarnz2e"/><stop offset="1" class="sk_xim0ag"/></radialGradient><radialGradient id="i8z60vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 .96346 -.87532 -1.2526 15.68 9.806)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="rpngv328y"/><stop offset="1" class="t-rizvbci"/></radialGradient><radialGradient id="irCHEVn" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 .5625 -.53002 -.60363 18.807 9.776)" gradientUnits="userSpaceOnUse"><stop class="xp17b02vv"/><stop offset="1" class="iu34ngpem"/></radialGradient><radialGradient id="iAuTJ6b" cx="0" cy="0" r="1" gradientTransform="matrix(.63766 .79277 -.77436 .62286 13.053 9.776)" gradientUnits="userSpaceOnUse"><stop class="dp-wqtbjr"/><stop offset="1" class="b9skxcbce"/></radialGradient><radialGradient id="iaxQkid" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.0781 .32438 -.60175 11.697 6.214)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="sdopbqbnf"/><stop offset="1" class="bj8dg0b8l"/></radialGradient><radialGradient id="iCJwfdb" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 10.58 7.516)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="ixiw7Nc" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 23.257 4.851)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="i2Kf17d" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 3.836 4.541)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iyXQn0l" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 9.77 4.851)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwdleKr" cx="0" cy="0" r="1" gradientTransform="rotate(131.102 6.394 8.24)scale(2.51937 2.50772)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="oqfgbbi5b"/><stop offset="1" class="bvgzffjne"/></radialGradient><radialGradient id="iFovmgd" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 0 0 1.01563 14.557 9.495)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="r7-2wfbcc"/><stop offset="1" class="me2qedj2f"/></radialGradient><radialGradient id="ia6Q7le" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 -.67969 .45049 .56959 16.682 8.917)" gradientUnits="userSpaceOnUse"><stop class="mky8h2bzd"/><stop offset="1" class="dudenh09d"/></radialGradient><radialGradient id="iUCPwrb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.22 -1.443)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="icYySuN" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 12.994 9.089)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iZfcJcb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 14.552 -4.775)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iHUahhe" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 19.658 9.089)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="ifvdSwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06861 1.1704 -1.32316 -1.20809 16.615 2.453)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iHZGaVd" cx="0" cy="0" r="1" gradientTransform="matrix(.57433 -.42319 .25665 .34832 16.607 2.55)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwpylec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35276 -1.76557 0 15.994 2.496)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="smf6lpbrg"/><stop offset="1" class="h4ps77q_r"/></radialGradient><linearGradient id="iBGggtc" x1="8.354" x2="8.12" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wjgmmu2gq"/><stop offset="1" class="a7d2l_-4t"/></linearGradient><linearGradient id="iwSpWAe" x1="23.423" x2="24.011" y1="28.188" y2="28.188" gradientUnits="userSpaceOnUse"><stop class="aosu0gbmr"/><stop offset="1" class="p7fclrrnf"/></linearGradient><linearGradient id="iKpNxNi" x1="15.424" x2="15.658" y1="28.979" y2="28.979" gradientUnits="userSpaceOnUse"><stop class="utflpqb7a"/><stop offset="1" class="k0l9ze_pq"/></linearGradient><linearGradient id="iAjKzvn" x1="16.549" x2="16.283" y1="30.022" y2="30.022" gradientUnits="userSpaceOnUse"><stop offset=".368" class="cgi88gv2t"/><stop offset="1" class="ehqj11bbt"/></linearGradient><linearGradient id="igYMrNc" x1="7.913" x2="7.913" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i8OHdZL" x1="20.359" x2="20.359" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iB7870d" x1="19.601" x2="19.805" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="i0cYndb" x1="20.736" x2="20.58" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ihZ8ljd" x1="8.933" x2="8.933" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i3YmUdc" x1="8.218" x2="8.367" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="ix94lod" x1="21.379" x2="21.379" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="i5Cpwir" x1="20.622" x2="20.825" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="irBmJac" x1="21.757" x2="21.6" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="irrycLb" x1="9.953" x2="9.953" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="itK9dec" x1="9.239" x2="9.387" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iO03fwe" x1="22.399" x2="22.399" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iNOiLgd" x1="21.642" x2="21.846" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iXRpDRc" x1="22.777" x2="22.621" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="i7kl0Ed" x1="10.974" x2="10.974" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iWwOBIc" x1="10.259" x2="10.407" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iewIeqd" x1="23.42" x2="23.42" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iBIanRb" x1="22.662" x2="22.866" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iYF91vc" x1="23.797" x2="23.641" y1="23.87" y2="23.87" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="il892Jq" x1="11.994" x2="11.994" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iNF4hvc" x1="11.279" x2="11.428" y1="23.698" y2="23.698" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="i4uy3yd" x1="24.44" x2="24.44" y1="24.792" y2="22.354" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="imRqQGW" x1="23.683" x2="23.886" y1="23.716" y2="23.716" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iamWsYd" x1="24.338" x2="18.619" y1="21.261" y2="21.261" gradientUnits="userSpaceOnUse"><stop class="aw5v51m2w"/><stop offset="1" class="epa4jwbux"/></linearGradient><linearGradient id="iKHOimb" x1="18.213" x2="13.4" y1="22.839" y2="19.276" gradientUnits="userSpaceOnUse"><stop offset=".388" class="xoq3wtioq"/><stop offset="1" class="shyqpdbhw"/></linearGradient><linearGradient id="ixusqle" x1="12.914" x2="12.914" y1="5.826" y2="7.839" gradientUnits="userSpaceOnUse"><stop class="hn2pq365w"/><stop offset="1" class="ckrbxabiw"/></linearGradient><linearGradient id="iHySmhe" x1="21.151" x2="16.798" y1="16.614" y2="16.614" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iATyoGd" x1="16.832" x2="15.994" y1="15.604" y2="15.639" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="idLKUTd" x1="15.994" x2="15.994" y1="16.743" y2="16.278" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i09yf1b" x1="15.994" x2="15.994" y1="13.909" y2="14.585" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="icxDjEc" x1="14.792" x2="15.11" y1="18.314" y2="17.479" gradientUnits="userSpaceOnUse"><stop class="i1fuj7kai"/><stop offset="1" class="qowbhoblz"/></linearGradient><linearGradient id="i5WTTwe" x1="18.954" x2="18.64" y1="14.066" y2="14.259" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAedIEc" x1="14.556" x2="14.242" y1="14.066" y2="14.259" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3TFEXJ" x1="22.43" x2="21.223" y1="14.094" y2="16.27" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iGQA5kL" x1="10.144" x2="11.602" y1="14.797" y2="14.67" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iKD7bzd" x1="21.473" x2="21.473" y1="13.722" y2="15.626" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="igPCvHd" x1="15.791" x2="15.791" y1="12.347" y2="11.964" gradientUnits="userSpaceOnUse"><stop class="dfdb-obom"/><stop offset="1" class="ykc__8bxx"/></linearGradient><linearGradient id="ilSsPFd" x1="22.878" x2="22.213" y1="6.729" y2="6.651" gradientUnits="userSpaceOnUse"><stop class="lqxvkgj5w"/><stop offset="1" class="omim8hb6o"/></linearGradient><linearGradient id="iGnutIe" x1="19.362" x2="21.79" y1="7.448" y2="6.013" gradientUnits="userSpaceOnUse"><stop class="o_xhqbdfz"/><stop offset="1" class="cm4ghn5oa"/></linearGradient><linearGradient id="iBURqYd" x1="16.422" x2="19.127" y1="7.073" y2="6.418" gradientUnits="userSpaceOnUse"><stop class="xgp1qchkh"/><stop offset="1" class="s3wqo851w"/></linearGradient><linearGradient id="iJAl6YN" x1="10.153" x2="12.446" y1="6.074" y2="7.816" gradientUnits="userSpaceOnUse"><stop class="xgzvgdboh"/><stop offset="1" class="a5j92oajv"/></linearGradient><filter id="iFGqjOd" width="6.055" height="2.589" x="6.611" y="23.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".375"/></filter><filter id="iQg26Db" width="6.055" height="4.091" x="18.732" y="21.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".375"/></filter><filter id="ircbAOd" width="1.02" height="3.045" x="7.221" y="21.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iMVRLrd" width="1.02" height="3.045" x="8.241" y="21.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iAjjYud" width="1.02" height="3.045" x="9.261" y="21.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iRzIFUb" width="1.02" height="3.045" x="10.282" y="21.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="i71w48b" width="1.02" height="3.045" x="11.302" y="21.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="ieOPRwe" width="6" height="2.728" x="7.08" y="19.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.686275 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.584314 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3528" result="effect2_innerShadow_13929_3528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.521569 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_3528" result="effect3_innerShadow_13929_3528"/></filter><filter id="iGBCbKb" width="6" height="2.728" x="18.908" y="19.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.588235 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3528" result="effect2_innerShadow_13929_3528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.709804 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_3528" result="effect3_innerShadow_13929_3528"/></filter><filter id="i0Bseec" width="8.261" height="7.961" x="11.864" y="16.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3528" result="effect2_innerShadow_13929_3528"/></filter><filter id="iQ0sKWc" width="2.557" height="2.672" x="11.685" y="5.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="il0uZ0d" width="1.521" height="1.521" x="11.84" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.643137 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iq0g8sd" width="2.416" height="2.353" x="17.968" y="5.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.717647 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iltI0sI" width="1.521" height="1.521" x="18.629" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.572549 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="inKYGDe" width="11.22" height="12.542" x="10.931" y="8.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3528" result="effect2_innerShadow_13929_3528"/></filter><filter id="iAEeKTT" width="3.747" height="4.9" x="13.978" y="13.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".5"/></filter><filter id="iPSgN0b" width="2.277" height="3.3" x="14.855" y="13.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".1"/></filter><filter id="iR4gdNb" width="3.718" height="1.573" x="14.134" y="17.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".05"/></filter><filter id="iYEWDTb" width=".787" height=".696" x="17.442" y="13.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".05"/></filter><filter id="i88Dbze" width=".891" height=".913" x="18.282" y="13.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".1"/></filter><filter id="iaQRyfe" width=".986" height="1.04" x="13.839" y="13.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".1"/></filter><filter id="iv5Uxab" width=".913" height=".705" x="13.084" y="13.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".05"/></filter><filter id="ipzsiHB" width="1.329" height="2.379" x="9.913" y="13.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".125"/></filter><filter id="iBAbMne" width="1.947" height="2.903" x="20.499" y="13.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".25"/></filter><filter id="im2Xkwe" width="1.535" height="1.534" x="21.971" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="il5BUle" width="1.535" height="1.534" x="8.483" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="i7uTfLc" width="2.656" height="2.656" x="14.668" y="8.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.443137 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="i8QulQc" width="1.646" height="1.646" x="11.84" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iDmsswc" width="1.646" height="1.646" x="18.504" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter><filter id="iREq0Yd" width="3.214" height="1.831" x="18.883" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".05"/></filter><filter id="iNhNJtW" width="2.847" height="3.566" x="15.985" y="3.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".05"/></filter><filter id="iX5BYSc" width="2.566" height="1.722" x="9.914" y="5.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3528" stdDeviation=".05"/></filter><filter id="iF9sWvd" width="1.812" height="1.813" x="15.088" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3528"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-crown-light" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a5j92oajv {
  stop-color: var(--svg-color--d99c45, #D99C45);
}

.a7d2l_-4t {
  stop-color: var(--svg-color--ff4c2c, #FF4C2C);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.aosu0gbmr {
  stop-color: var(--svg-color--ff4d0c, #FF4D0C);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.aw5v51m2w {
  stop-color: var(--svg-color--ffca34, #FFCA34);
}

.b3ssyu2ir {
  stop-color: var(--svg-color--b87175, #B87175);
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

.bm954bbaf {
  cx: 13.54px;
  cy: 13.917px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.btm953brw {
  stop-color: var(--svg-color--c18731, #C18731);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bvgzffjne {
  stop-color: var(--svg-color--377be9, #377BE9);
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
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

.cm2ynzezx {
  d: path("M8.241 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.cm4ghn5oa {
  stop-color: var(--svg-color--fbc46e, #FBC46E);
  stop-opacity: 0;
}

.d-y7wjh4h {
  d: path("M20.687 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.d0pq7p0hl {
  stop-color: var(--svg-color--d9a439, #D9A439);
}

.dfdb-obom {
  stop-color: var(--svg-color--ff7468, #FF7468);
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

.dvti4ibqx {
  d: path("M10.282 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e1zap2b6k {
  d: path("M18.112 13.724c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
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

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.epa4jwbux {
  stop-color: var(--svg-color--ffbc10, #FFBC10);
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

.fcxmlvlbk {
  d: path("M12.65 5.167c-.468.187-.824 1.205-.965 1.648l1.16 1.024l1.298-.961c-.801-1.453-1.149-1.637-1.297-1.68z");
}

.fiwhz1yao {
  stop-color: var(--svg-color--fad771, #FAD771);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
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

.fwcf4ds6u {
  stop-color: var(--svg-color--f2b056, #F2B056);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
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

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hgknd0bcu {
  d: path("M4.338 29.964c.766-3.875 3.281-10.032 11.656-10.032v.038l.012-.038c8.375 0 10.89 6.157 11.656 10.032z");
}

.hn2pq365w {
  stop-color: var(--svg-color--f6c164, #F6C164);
}

.i1fuj7kai {
  stop-color: var(--svg-color--e1ada5, #E1ADA5);
}

.i2r14vbib {
  stop-color: var(--svg-color--39b6de, #39B6DE);
}

.i3n99zbcs {
  fill: var(--svg-color--fb3310, #FB3310);
  d: path("M24.037 23.89h-.911v.82c0 .149.12.269.268.269h.375c.148 0 .268-.12.268-.268z");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ii6c7s39l {
  d: path("M23.748 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.iu34ngpem {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
  stop-opacity: 0;
}

.iwcw2ibei {
  d: path("M10.908 13.73a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.iyq1_fb9e {
  stop-color: var(--svg-color--e4bb48, #E4BB48);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.izxaz-bvs {
  stop-color: var(--svg-color--3c7dcd, #3C7DCD);
}

.j0k3id93s {
  stop-color: var(--svg-color--984900, #984900);
  stop-opacity: 0;
}

.j8vxk9r3t {
  fill: var(--svg-color--e12706, #E12706);
  d: path("M11.916 23.904h-.911v.82c0 .149.12.269.268.269h.375c.148 0 .268-.12.268-.268z");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jdm59-bck {
  stop-color: var(--svg-color--d28b7d, #D28B7D);
}

.jnpel9bup {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
}

.jo4sxnm8i {
  stop-color: var(--svg-color--e0613c, #E0613C);
}

.jpa7s1h3a {
  d: path("M11.169 17.693a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.69.238 5.556");
}

.jrd3jzgth {
  stop-color: var(--svg-color--dd7423, #DD7423);
  stop-opacity: 0;
}

.jxiqgfbai {
  d: path("M16.549 29.964h-1.086v-6.282h1.086z");
}

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jzfasvbbp {
  cx: 22.739px;
  cy: 5.184px;
  r: 0.767px;
}

.k_vmfilmc {
  d: path("M24.908 20.971a1 1 0 0 0-1-1h-5v2.579h5.2a.8.8 0 0 0 .8-.8z");
}

.k0l9ze_pq {
  stop-color: var(--svg-color--da7c13, #DA7C13);
  stop-opacity: 0;
}

.kfayvkisl {
  cx: 17.494px;
  cy: 28.386px;
  r: 0.547px;
}

.kfhq2vx5n {
  stop-color: var(--svg-color--c68e33, #C68E33);
}

.kh0u3slld {
  fill: var(--svg-color--dea99c, #DEA99C);
  d: path("m15.611 14.214l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.645-.407-.765 0");
}

.kkaqah18a {
  d: path("M21.707 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.kowfi484h {
  cx: 15.994px;
  cy: 2.942px;
  r: 0.906px;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kz6jvgbzd {
  stop-color: var(--svg-color--e0a155, #E0A155);
}

.l0yglmb3r {
  stop-color: var(--svg-color--e5c652, #E5C652);
}

.l2jyntb4f {
  stop-color: var(--svg-color--ffad23, #FFAD23);
}

.l7-dtlm-e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 7.268c.07.081.261.227.461.164c.2-.062 1.719-1.036 2.453-1.515");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.ldyj_nb1e {
  cx: 9.25px;
  cy: 5.184px;
  r: 0.767px;
}

.lhbsumjnz {
  d: path("M20.855 16.178c.335-.01.65-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02q.256-.546.346-1.18z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll-sfjbvs {
  fill: var(--svg-color--ffbf46, #FFBF46);
  d: path("M16.549 29.964h-1.086v-6.282h1.086z");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lqxvkgj5w {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
}

.ltsxllb3q {
  stop-color: var(--svg-color--d37902, #D37902);
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

.mky8h2bzd {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mqzky-b6t {
  stop-color: var(--svg-color--ffcc36, #FFCC36);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mvaqivyxk {
  stop-color: var(--svg-color--cd9d50, #CD9D50);
  stop-opacity: 0;
}

.mx5qf9bzw {
  stop-color: var(--svg-color--ffab48, #FFAB48);
}

.n2y_l5h3h {
  d: path("M13.81 13.536a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.n4msb7ugs {
  cx: 12.663px;
  cy: 9.409px;
  r: 0.823px;
}

.n5f-q5igg {
  d: path("M20.916 16.27c.065-1.064.129-2.127.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.ncr9djbkt {
  fill: var(--svg-color--fb3310, #FB3310);
  d: path("M19.482 22.388h1.822v2.323c0 .148-.12.268-.268.268h-.375a.27.27 0 0 1-.268-.265a.27.27 0 0 1-.268.265h-.375a.27.27 0 0 1-.268-.268zm1.822 0v2.323c0 .148.12.268.268.268h.375a.27.27 0 0 0 .268-.265a.27.27 0 0 0 .268.265h.375c.148 0 .268-.12.268-.268v-.821z");
}

.nd4srkbik {
  stop-color: var(--svg-color--fa865b, #FA865B);
  stop-opacity: 0;
}

.nt6io9bbg {
  stop-color: var(--svg-color--c5838c, #C5838C);
  stop-opacity: 0;
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
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

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o297js0_g {
  cx: 15.994px;
  cy: 20.518px;
  rx: 2.32px;
  ry: 2.297px;
}

.o375d620d {
  stop-color: var(--svg-color--e08711, #E08711);
  stop-opacity: 0;
}

.o4kt6qgcl {
  stop-color: var(--svg-color--d28b7d, #D28B7D);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odv1wqwrs {
  d: path("M15.994 17.825c-.508 0-.985-.119-1.386-.328c-.137-.07-.284.085-.198.209c.335.508.919.846 1.584.846c.664 0 1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.328");
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

.p6e0x9tlj {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.592 14.405l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.383.484-.756l-.495-1.838c-.105-.407-.504-.407-.615 0");
}

.p7fclrrnf {
  stop-color: var(--svg-color--ff4d0c, #FF4D0C);
  stop-opacity: 0;
}

.p80wfibmc {
  d: path("M10.95 13.07a1.62 1.62 0 0 0-1.393 1.593c0 .859.673 1.56 1.521 1.607a78 78 0 0 1-.129-3.2");
}

.pd-kjcckg {
  stop-color: var(--svg-color--ffc95d, #FFC95D);
  stop-opacity: 0;
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

.prxm8ubjj {
  cx: 22.026px;
  cy: 9.418px;
  r: 0.817px;
}

.pwdyrab-n {
  d: path("m9.11 5.008l1.287 7.094a.25.25 0 0 0 .246.205h10.702a.25.25 0 0 0 .246-.206l1.287-7.093l-3.37 2.108a.495.495 0 0 1-.666-.13l-.666-.946c-.551-.784-1.11-1.581-1.371-1.89c-.38-.454-.651-.477-.807-.477h-.007c-.156 0-.427.023-.808.476c-.26.31-.82 1.106-1.37 1.891c-.232.33-.462.657-.667.945a.495.495 0 0 1-.667.13z");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.pxse0-u4m {
  cx: 19.327px;
  cy: 9.409px;
  r: 0.823px;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q5a0_7mqo {
  stop-color: var(--svg-color--ff6e46, #FF6E46);
}

.qk8v1bc2n {
  cx: 19.39px;
  cy: 4.609px;
  r: 0.761px;
}

.ql1-3v45r {
  stop-color: var(--svg-color--b87675, #B87675);
}

.qowbhoblz {
  stop-color: var(--svg-color--e1ada5, #E1ADA5);
  stop-opacity: 0;
}

.qq1243s9v {
  d: path("M7.22 21.846h1.021v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r5r21mbtx {
  d: path("m15.611 14.214l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.645-.407-.765 0");
}

.r7-2wfbcc {
  stop-color: var(--svg-color--467ec1, #467EC1);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r84slnqkj {
  stop-color: var(--svg-color--d8948e, #D8948E);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rez3ddccp {
  stop-color: var(--svg-color--e5780c, #E5780C);
}

.rgangdc7y {
  stop-color: var(--svg-color--416ec4, #416EC4);
  stop-opacity: 0;
}

.rpngv328y {
  stop-color: var(--svg-color--e1754f, #E1754F);
}

.rrwvrg1ho {
  stop-color: var(--svg-color--ff6e46, #FF6E46);
  stop-opacity: 0;
}

.rwrql1b8d {
  d: path("M21 15.626q.057-.952.11-1.904a.956.956 0 0 1-.11 1.904");
}

.s-qqz8oax {
  stop-color: var(--svg-color--e68600, #E68600);
  stop-opacity: 0;
}

.s20fc4arp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.112 13.724c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.s3wqo851w {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
  stop-opacity: 0;
}

.s8wgbib2e {
  d: path("M7.08 20.971a1 1 0 0 1 1-1h5v2.579h-5.2a.8.8 0 0 1-.8-.8z");
}

.sblhzud6f {
  stop-color: var(--svg-color--e11f40, #E11F40);
}

.sdopbqbnf {
  stop-color: var(--svg-color--e4ad53, #E4AD53);
}

.shnlphbde {
  d: path("M14.625 14.323c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
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

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sy6a29bji {
  stop-color: var(--svg-color--dda44f, #DDA44F);
  stop-opacity: 0;
}

.t-rizvbci {
  stop-color: var(--svg-color--e1754f, #E1754F);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t3kcpjbyb {
  cx: 15.996px;
  cy: 9.409px;
  r: 1.328px;
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.taakstd9a {
  d: path("M19.667 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.temm9m1gz {
  d: path("M22.727 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
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

.u_7404bbu {
  stop-color: var(--svg-color--ff834e, #FF834E);
}

.u8ozf6b8x {
  stop-color: var(--svg-color--e5780c, #E5780C);
  stop-opacity: 0;
}

.ucl97ybiq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.603 13.263c-.653 0-1.205.45-1.355 1.06a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.ufab9bcqz {
  stop-color: var(--svg-color--416ec4, #416EC4);
}

.us1u98b3g {
  d: path("M23.635 22.456c2.514 2.141 3.575 5.222 4.027 7.508h-4.027z");
}

.ut-12mb9a {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.643 17.43a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.271c.349.528.955.879 1.646.879a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.utflpqb7a {
  stop-color: var(--svg-color--da7c13, #DA7C13);
}

.utmko7bie {
  fill: var(--svg-color--000, #000);
  d: path("M17.667 14.428a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uy_ysvgeb {
  d: path("M18.178 13.536a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.v-aq_fb5e {
  cx: 9.966px;
  cy: 9.418px;
  r: 0.817px;
}

.v1k_mhzfg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
  stop-opacity: 0;
}

.v4gg9p-ym {
  stop-color: var(--svg-color--ff8258, #FF8258);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vsg8c7gji {
  stop-color: var(--svg-color--ff432e, #FF432E);
}

.vsszmllkn {
  d: path("M11.132 16.178a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
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

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.we5kvqbpm {
  cx: 15.994px;
  cy: 20.206px;
  r: 3.98px;
}

.wjgmmu2gq {
  stop-color: var(--svg-color--ff4c2c, #FF4C2C);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.x-hxw-bgc {
  cx: 13.54px;
  cy: 13.917px;
  rx: 0.39px;
  ry: 0.197px;
}

.x36tsjbay {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m10.065 5.862l2.265 1.422");
}

.x9knvh_3c {
  stop-color: var(--svg-color--ff5730, #FF5730);
}

.xgp1qchkh {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
}

.xgzvgdboh {
  stop-color: var(--svg-color--e4aa42, #E4AA42);
}

.xmc2l2-sl {
  stop-color: var(--svg-color--ffc95d, #FFC95D);
}

.xmck5lbbx {
  d: path("M9.261 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.xoq3wtioq {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
}

.xp17b02vv {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
}

.xrm2prbkt {
  d: path("M18.973 14.31a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xslzggb2v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.135 3.807c.11.032.387.172.625.485c.237.312 1.38 1.984 1.922 2.781");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y78x6obne {
  d: path("M11.302 21.846h1.02v2.646a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ykc__8bxx {
  stop-color: var(--svg-color--ff865b, #FF865B);
  stop-opacity: 0;
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yp_h4cxpw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.385 13.263c.653 0 1.204.45 1.355 1.06a.274.274 0 0 1-.268.34H17.24a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.128");
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1e4imbuu {
  stop-color: var(--svg-color--e2aa40, #E2AA40);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z2x1q0bwg {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 14.428a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
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

.zl0i2nl5t {
  stop-color: var(--svg-color--fca135, #FCA135);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zupcoccwr {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
}

</style>
