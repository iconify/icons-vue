<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLcs2Yb)"><path fill="url(#iNW7HLc)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#iCs15ev)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#i83vnAd)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#ibvqIpe)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#i5LGepc)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#iSuCJVc)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#iZAISwb)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#iLJR5jb)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#ihZe8pc)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#i1JCQRd)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#idopdKd)" clip-rule="evenodd" class="apq__yovd"/><path fill="url(#iVZKiDr)" clip-rule="evenodd" class="apq__yovd"/></g><g filter="url(#iF6QVwc)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iYdC04d)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i7vkVTd)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#irzhwUd)"><path fill="url(#izGJMde)" class="u7zreccre"/><path fill="url(#iEsiYmg)" class="u7zreccre"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#iMTKUNd)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#iFg1mXc)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#i8TFtjn)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#ihI9oTh)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iSjphHe)"><path class="p4atghb8h"/></g><g filter="url(#iKNdtrH)"><path class="ucq3z1bcr"/></g><g filter="url(#iXK7W9d)"><path class="sbbt-6b7n"/></g><g filter="url(#iyyKRNc)"><path class="ay_tpr1ro"/></g><g filter="url(#iH06F5b)"><path class="xnf9zsbcq"/></g><path fill="url(#ilez79L)" class="hw860-bkw"/><path fill="url(#iSXBdIb)" class="hw860-bkw"/><path fill="url(#ib914xd)" class="hw860-bkw"/><g filter="url(#iE797pd)"><path fill="url(#iq39nHd)" class="u5bjt8cdp"/></g><path fill="url(#iELdlqb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iBqD1Xb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iiItqld)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iGVyd2d)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#i5nc0Sc)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iQodSWd)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iUzJ9JS)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iYRVChc)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iHc2wiw)" class="twba206ho"/><path fill="url(#idQamRc)" class="twba206ho"/><path fill="url(#iBVul5c)" class="giwv3_xuk"/><g filter="url(#ifEzcqd)"><path class="jgab0yb4f"/></g><g filter="url(#iy4HVEe)"><path class="a65rs5a6h"/></g><g filter="url(#iZSpF9d)"><path class="swira1fyd"/></g><g filter="url(#i4Ri4yd)"><path class="wzn2a8b8n"/></g><g filter="url(#i2JgAJd)"><path stroke="url(#ioZXgLe)" class="bdk4dmb5b"/></g><g filter="url(#izZkjsr)"><path stroke="url(#i4O2smb)" class="gwm_2mjil"/></g><g filter="url(#iREG4sd)"><path stroke="url(#iz0d3ff)" class="y2ly1lryk"/></g><g filter="url(#iiIygbb)"><path stroke="url(#iJwKJNb)" class="am6k_ubte"/></g><g filter="url(#iLm8kxc)"><path stroke="url(#ivFlTre)" class="c549xi8ae"/></g><g filter="url(#iwMgweb)"><path class="vcz9qnm9q"/></g><g filter="url(#iOjC54b)"><path class="hzaq54bmy"/></g><g filter="url(#isN7qXf)"><path fill="url(#ifMcxrb)" class="qmqoq5wah"/></g><path fill="url(#ipXkmvd)" class="qmqoq5wah"/><g filter="url(#iezi0kd)"><path fill="url(#iZcoFsh)" class="jopb5_jfz"/><path fill="url(#iomKu8D)" class="jopb5_jfz"/></g><g filter="url(#iZ9yite)"><path class="a8h8ipb3k"/><path fill="url(#iZwVrJd)" class="zbrgh-b8a"/></g><g filter="url(#imLV9fb)"><path class="z1puarbvc"/><path fill="url(#i7HMYye)" class="eqw35acuf"/></g><g filter="url(#iwIzCmS)"><path fill="url(#iV0xDud)" class="n0ehll2xi"/><path fill="url(#iNKSLvc)" class="n0ehll2xi"/><path fill="url(#iOQApob)" class="n0ehll2xi"/><path fill="url(#iuEbDCb)" class="n0ehll2xi"/><path fill="url(#iwNxtsb)" class="n0ehll2xi"/><path fill="url(#ifjSZbd)" class="n0ehll2xi"/><path fill="url(#iQdYDke)" class="n0ehll2xi"/><path fill="url(#iXFN0Jc)" class="n0ehll2xi"/></g><path fill="url(#imyGuce)" class="n0ehll2xi"/><path fill="url(#iQIt2Ic)" class="n0ehll2xi"/><g filter="url(#i9PrYGc)"><path class="sqb-msb-y"/></g><g filter="url(#ixrPbHc)"><path class="lnfhtccyc"/><path fill="url(#ijKHFIU)" class="w7qmd2b-u"/><path fill="url(#iv72E5b)" class="w7qmd2b-u"/><path fill="url(#iuSe2Me)" class="w7qmd2b-u"/><path fill="url(#iaAHbQc)" class="w7qmd2b-u"/></g><g filter="url(#iSM5f4b)"><path stroke="url(#i3eAS9c)" class="z2vq38laf"/></g><path class="qe_78ebio"/><g filter="url(#ioPqAtT)"><path class="oya7196ei"/></g><g filter="url(#iFS7K3g)"><path class="buc0d_bnb"/></g><g filter="url(#iEK9FEd)"><path class="loi5lgg2x"/></g><g filter="url(#ij7pIFO)"><path clip-rule="evenodd" class="u_34jf9mj"/></g><path class="nifqy9ecx"/><path fill="url(#iYxhTNg)" class="r0w7kiv9d"/><path class="rd7jtnb6n"/><g filter="url(#iW0SC1c)"><path class="pyjisbbnc"/><path fill="url(#iH2QdSc)" class="c27tipb9q"/></g><g filter="url(#iJkk0Pe)"><path fill="url(#i7ssXic)" class="owtwvuboe"/></g><path class="mqkgymbpq"/><path fill="url(#ie7R4ib)" class="h6brxyblx"/><path class="p3dm0tghu"/><g filter="url(#iJGt7pd)"><path fill="url(#igLIpjb)" class="zu1-zdlnf"/></g><g filter="url(#ic0BcKd)"><ellipse transform="rotate(-27.914 13.992 13.064)" class="th-ps6b7f"/><ellipse fill="url(#iT5Sn8U)" transform="rotate(-27.914 13.992 13.064)" class="ptwsj8bwp"/></g><g filter="url(#iRNSzQe)"><path class="yxrzstbma"/></g><g filter="url(#ixTWVGb)"><path class="p09sgqdgo"/></g><g filter="url(#isWzcmX)"><path stroke="url(#ieAyt6d)" class="oph01k6ia"/></g><g filter="url(#iBhqKmd)"><path class="z9e-el7mu"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iCs15ev" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .933 15.318)scale(4.80763 6.00571)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="i83vnAd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.099 10.374)scale(3.63527 4.77645)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="ibvqIpe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.282 9.85)scale(2.24996 1.72766)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="i5LGepc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.646 9.305)scale(2.58744 1.82262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iSuCJVc" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.999 13.34)scale(3.08811 4.28676)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iZAISwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50683 1.50693 -2.1059 -2.10576 22.654 7.536)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iLJR5jb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92737 .56072 -1.16934 -4.01938 24.406 12.898)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="ihZe8pc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.874 9.7)scale(3.03427 3.8652)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i1JCQRd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.455 -2.515)scale(2.92748 2.31547)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="idopdKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5722 .16491 -.26721 2.54742 10.136 12.86)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iVZKiDr" cx="0" cy="0" r="1" gradientTransform="matrix(-.8761 -3.87243 1.39764 -.3162 21.9 12.18)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="izGJMde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.497 20.785)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iEsiYmg" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.42 22.473)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ilez79L" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="va-8to-0f"/><stop offset="1" class="ljv0l9wbv"/></radialGradient><radialGradient id="iSXBdIb" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="smnqffnel"/><stop offset="1" class="jknxnjb8w"/></radialGradient><radialGradient id="ib914xd" cx="0" cy="0" r="1" gradientTransform="rotate(77.963 .104 26.074)scale(1.04894 5.75403)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="s3rfzh4ga"/><stop offset="1" class="aewjbccqi"/></radialGradient><radialGradient id="iq39nHd" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="b1xnaurjw"/><stop offset="1" class="xvexp0bjq"/></radialGradient><radialGradient id="iELdlqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iBqD1Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iiItqld" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iGVyd2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="i5nc0Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iQodSWd" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iUzJ9JS" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iYRVChc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iHc2wiw" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="qq8pp_7zq"/><stop offset=".482" class="blko_hazg"/></radialGradient><radialGradient id="idQamRc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="jwq5cabxr"/><stop offset="1" class="yt9en_n3k"/></radialGradient><radialGradient id="iBVul5c" cx="0" cy="0" r="1" gradientTransform="rotate(53.51 -11.7 25.823)scale(3.1004 3.53574)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="exfuzbt0n"/><stop offset="1" class="w4ky7s-1q"/></radialGradient><radialGradient id="ipXkmvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68338 -1.2581 1.4256 -.77436 11.247 15.47)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iZcoFsh" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 43.277 -40.84)scale(2.85826 3.4898)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iomKu8D" cx="0" cy="0" r="1" gradientTransform="matrix(1.26161 0 0 .5432 21.725 12.005)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iZwVrJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.57845 -.11741 .09178 1.2339 21.147 13.906)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i7HMYye" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.873 6.894)scale(1.10391)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iV0xDud" cx="0" cy="0" r="1" gradientTransform="matrix(-6.79886 3.13518 -4.19638 -9.10015 19.545 13.226)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iNKSLvc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27927 1.00295 -.69844 -1.58725 18.616 14.12)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iOQApob" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 20.975 .146)scale(4.3222 5.48407)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iuEbDCb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.343 7.70795 -9.63484 -1.67874 17.625 12.791)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iwNxtsb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.2192 1.41674 -2.4392 -12.42922 18.449 15.036)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="ifjSZbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20302 1.47643 0 18.962 12.789)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iQdYDke" cx="0" cy="0" r="1" gradientTransform="scale(1.57252 1.37211)rotate(-90 9.147 0)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iXFN0Jc" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.03 12.08)scale(3.49375 2.79558)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="imyGuce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34364 0 0 -6.73822 21.883 14.344)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="ijKHFIU" cx="0" cy="0" r="1" gradientTransform="matrix(-.47623 -2.13682 .65854 -.14677 17.376 15.104)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iaAHbQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81479 0 0 -.22779 17.126 15.325)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iYxhTNg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84815 -1.34908 0 18.838 13.164)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iH2QdSc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.545 2.071)scale(.39546 .54446)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ie7R4ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84816 -1.34909 0 14.275 13.164)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iT5Sn8U" cx="0" cy="0" r="1" gradientTransform="matrix(-.00809 -.51649 .62084 -.00972 13.976 13.392)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="iLcs2Yb" width="15.95" height="16.45" x="8.706" y="4.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iF6QVwc" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iYdC04d" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23853"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23853" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23853"/></filter><filter id="i7vkVTd" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23853"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23853" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23853"/></filter><filter id="irzhwUd" width="6.728" height="3.692" x="13.616" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iMTKUNd" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".5"/></filter><filter id="iFg1mXc" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="i8TFtjn" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="ihI9oTh" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iSjphHe" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.364706 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iKNdtrH" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iXK7W9d" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iyyKRNc" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iH06F5b" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iE797pd" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.360784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="ifEzcqd" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iy4HVEe" width="1.286" height="2.978" x="23.933" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iZSpF9d" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="i4Ri4yd" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="i2JgAJd" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="izZkjsr" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iREG4sd" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iiIygbb" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iLm8kxc" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iwMgweb" width="5.441" height="3.076" x="17.747" y="6.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".375"/></filter><filter id="iOjC54b" width="5.461" height="3.084" x="17.805" y="6.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".375"/></filter><filter id="isN7qXf" width="3.514" height="3.364" x="9.976" y="12.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iezi0kd" width="3.364" height="3.614" x="19.92" y="11.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iZ9yite" width="3.246" height="3.246" x="19.98" y="12.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".25"/></filter><filter id="imLV9fb" width="2.946" height="2.946" x="10.205" y="12.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".175"/></filter><filter id="iwIzCmS" width="10.654" height="11.621" x="11.229" y="8.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="i9PrYGc" width="2.962" height="3.803" x="14.906" y="12.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".25"/></filter><filter id="ixrPbHc" width="2.462" height="3.303" x="15.325" y="12.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".125"/></filter><filter id="iSM5f4b" width="3.852" height="1.577" x="14.63" y="16.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".05"/></filter><filter id="ioPqAtT" width="3.129" height="1.344" x="17.55" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iFS7K3g" width="3.129" height="1.344" x="12.434" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iEK9FEd" width="2.555" height="1.131" x="12.576" y="10.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="ij7pIFO" width="2.555" height="1.132" x="18.239" y="10.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23853"/></filter><filter id="iW0SC1c" width=".813" height=".719" x="18.075" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".05"/></filter><filter id="iJkk0Pe" width=".914" height=".937" x="18.958" y="12.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".1"/></filter><filter id="iJGt7pd" width="1.013" height="1.069" x="14.313" y="12.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".1"/></filter><filter id="ic0BcKd" width=".945" height=".727" x="13.519" y="12.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".05"/></filter><filter id="iRNSzQe" width="2.336" height=".995" x="18.284" y="10.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".1"/></filter><filter id="ixTWVGb" width="2.336" height=".995" x="12.585" y="10.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".1"/></filter><filter id="isWzcmX" width="1.169" height="2.387" x="13.234" y="6.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".1"/></filter><filter id="iBhqKmd" width="6.651" height="3.457" x="15.982" y="7.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23853" stdDeviation=".375"/></filter><linearGradient id="iNW7HLc" x1="21.463" x2="15.05" y1="6.52" y2="17.77" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="ioZXgLe" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="zrsmq2u6o"/><stop offset="1" class="mcp_a12ev"/><stop offset="1" class="qg7eszk4c"/></linearGradient><linearGradient id="i4O2smb" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iz0d3ff" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iJwKJNb" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="ivFlTre" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="ifMcxrb" x1="9.976" x2="11.918" y1="13.88" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iQIt2Ic" x1="16.556" x2="16.556" y1="10.732" y2="12.044" gradientUnits="userSpaceOnUse"><stop class="cjqyqacme"/><stop offset="1" class="psgk459yv"/></linearGradient><linearGradient id="iv72E5b" x1="15.575" x2="16.556" y1="15.18" y2="15.18" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iuSe2Me" x1="16.556" x2="16.556" y1="15.919" y2="15.264" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="i3eAS9c" x1="15.444" x2="15.926" y1="17.489" y2="16.744" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="i7ssXic" x1="19.651" x2="19.323" y1="13.221" y2="13.423" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igLIpjb" x1="15.053" x2="14.725" y1="13.221" y2="13.423" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieAyt6d" x1="13.306" x2="13.818" y1="6.521" y2="7.843" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-juggling-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a65rs5a6h {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.358 18.55l.436 2.127");
}

.a8h8ipb3k {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M21.603 14.911a1.123 1.123 0 1 0 0-2.245a1.123 1.123 0 0 0 0 2.245");
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.aewjbccqi {
  stop-color: var(--svg-color--a27671, #A27671);
  stop-opacity: 0;
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.am6k_ubte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.981 17.139c.11.172.625 1.078 1.282 1.273");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.apq__yovd {
  fill-rule: evenodd;
  d: path("M24.068 15.262a3.4 3.4 0 0 0 .338-1.492c0-.488-.1-.947-.28-1.364h.005a3.3 3.3 0 0 0-.294-.537l-.002-.003a3.4 3.4 0 0 1-.55-1.851v-.01c0-.68-2.591-.239-2.931-.773c-.612-.962.707-2.677-.518-2.677a.56.56 0 0 1-.476-.243a3.46 3.46 0 0 0-2.804-1.439c-1.153 0-2.18.571-2.803 1.439a.59.59 0 0 1-.476.243l-.09.001c-1.187.03.838 1.539.24 2.478c-.34.534-3.6.29-3.6.97v.01c0 .657-.19 1.302-.55 1.852l-.002.004a3.45 3.45 0 0 0-.23 3.392a.54.54 0 0 1 0 .476a3.4 3.4 0 0 0-.339 1.47a3.36 3.36 0 0 0 3.365 3.365h8.971a3.36 3.36 0 0 0 3.364-3.364c0-.53-.127-1.026-.338-1.47a.54.54 0 0 1 0-.477M11.25 12.468h-.013l1.253 2.463c.13 2.93 1.273 0 4.065 0s4.01 3.26 4.14.331l1.187-3.342c-.056-1.302-.999-1.393-1.187-1.393H17.33c-1.33 0-2.584-.65-3.334-1.75a.276.276 0 0 0-.483.054l-.086.203a2.4 2.4 0 0 1-1.297 1.312q-.028.013-.054.021c-.246.128-.825.512-.846 1.504l.01.32z");
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.ay_tpr1ro {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b1xnaurjw {
  stop-color: var(--svg-color--b38f7a, #B38F7A);
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bdk4dmb5b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m28.692 20.295l-.937 1.75");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.blko_hazg {
  stop-color: var(--svg-color--a6846b, #A6846B);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.buc0d_bnb {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M15.363 13.193c-.277-.488-.7-.873-1.607-.873c-.398 0-.78.11-1.122.385c-.28.227-.243.518-.025.627l.58.332c.682-.22 1.436-.25 2.174-.47");
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c27tipb9q {
  d: path("M18.771 12.863c.067.088-.072.197-.23.315s-.275.201-.342.112c-.066-.088.008-.256.166-.374c.158-.119.34-.142.406-.053");
}

.c549xi8ae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.77 17.467c.177.245.618 1.078 1.72 1.594");
}

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.cjqyqacme {
  stop-color: var(--svg-color--7b4c54, #7B4C54);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eqw35acuf {
  d: path("M11.678 14.911a1.123 1.123 0 1 0 0-2.245a1.123 1.123 0 0 0 0 2.245");
}

.exfuzbt0n {
  stop-color: var(--svg-color--8a4d60, #8A4D60);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.giwv3_xuk {
  d: path("M14.621 18.246c0-.99.9-1.794 2.012-1.794c1.11 0 2.011.803 2.011 1.794v2.326c0 .991-.9 1.794-2.011 1.794s-2.012-.803-2.012-1.794z");
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gwm_2mjil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.177 19.865c.177.245.832.742 1.472.84");
}

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.h6brxyblx {
  d: path("M14.273 12.666a.933.933 0 0 0-.899 1.178h1.803a1 1 0 0 0 .033-.245a.94.94 0 0 0-.937-.934");
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hzaq54bmy {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M21.252 8.376h-2.19a.508.508 0 1 1 .082-1.011c.568.09 1.322.216 1.827.341c1.142.284 1.457.84 1.545 1.236a1.6 1.6 0 0 0-1.264-.566");
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i7zyuv8vr {
  stop-color: var(--svg-color--ede7f3, #EDE7F3);
}

.i8j0jyb4u {
  stop-color: var(--svg-color--b8a734, #B8A734);
}

.i8skpb2jz {
  stop-color: var(--svg-color--5d5565, #5D5565);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jgab0yb4f {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jknxnjb8w {
  stop-color: var(--svg-color--95646c, #95646C);
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jopb5_jfz {
  d: path("M21.602 15.47a1.682 1.682 0 1 0 0-3.364a1.682 1.682 0 0 0 0 3.365");
}

.jwq5cabxr {
  stop-color: var(--svg-color--765443, #765443);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.ku63lg_wt {
  stop-color: var(--svg-color--e8e2ec, #E8E2EC);
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljv0l9wbv {
  stop-color: var(--svg-color--a87b73, #A87B73);
}

.lnfhtccyc {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m16.157 13.411l-.556 1.777a.564.564 0 0 0 .544.731h.822a.565.565 0 0 0 .545-.73l-.556-1.778c-.119-.394-.675-.394-.8 0");
}

.loi5lgg2x {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m13.005 11.93l-.005.002a.28.28 0 0 1-.288-.48l.002-.001l.003-.002l.01-.006l.033-.019q.045-.024.122-.061c.103-.05.25-.112.428-.17a2.9 2.9 0 0 1 1.389-.113a.28.28 0 1 1-.098.552c-.416-.074-.817 0-1.12.096a3 3 0 0 0-.453.19z");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m0zt7_pbu {
  stop-color: var(--svg-color--c7a08f, #C7A08F);
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.m9gf32bwp {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcp_a12ev {
  stop-color: var(--svg-color--997971, #997971);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mqkgymbpq {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.057 12.381c-.683 0-1.26.471-1.417 1.107a.287.287 0 0 0 .28.356h2.333a.24.24 0 0 0 .237-.284a1.465 1.465 0 0 0-1.433-1.179");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mug1r-bxu {
  stop-color: var(--svg-color--b58f71, #B58F71);
}

.n0ehll2xi {
  d: path("M11.238 12.468h.013l-.01-.277l-.012-.32c.022-.992.6-1.376.847-1.504q.025-.008.054-.021l.053-.022a2.4 2.4 0 0 0 1.244-1.29l.086-.203a.276.276 0 0 1 .482-.053a4.04 4.04 0 0 0 3.334 1.75h3.366c.189 0 1.132.09 1.188 1.392l-.124 3.212c-.13 2.93-2.417 4.897-5.21 4.897c-2.792 0-5.08-1.967-5.21-4.897z");
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nifqy9ecx {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.056 12.381c.683 0 1.26.471 1.416 1.107a.287.287 0 0 1-.28.356H17.86a.24.24 0 0 1-.237-.284a1.46 1.46 0 0 1 1.433-1.179");
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok2r3obil {
  stop-color: var(--svg-color--634d93, #634D93);
}

.okwd93kys {
  width: 15.516px;
  height: 1.742px;
  x: 9.003px;
  y: 9.238px;
  rx: 0.871px;
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.oph01k6ia {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.534 6.95c.024.254.245 1.209.569 1.787");
}

.owtwvuboe {
  d: path("M19.671 13.476a.9.9 0 0 0-.242-.484l-.271.298l.122.239z");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.oya7196ei {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.75 13.193c.278-.488.7-.873 1.608-.873c.397 0 .78.11 1.121.385c.281.227.244.518.026.627l-.581.332c-.682-.22-1.435-.25-2.174-.47");
}

.p09sgqdgo {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.621 11.308c-.337-.082-1.176-.041-1.736.36");
}

.p3dm0tghu {
  fill: var(--svg-color--000, #000);
  d: path("M14.808 13.598a.53.53 0 0 0-.534-.534a.532.532 0 0 0-.475.78h.945a.5.5 0 0 0 .064-.246");
}

.p4atghb8h {
  fill: var(--svg-color--c59883, #C59883);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.psgk459yv {
  stop-color: var(--svg-color--b18377, #B18377);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.ptwsj8bwp {
  cx: 13.992px;
  cy: 13.064px;
  rx: 0.407px;
  ry: 0.206px;
}

.pyjisbbnc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.771 12.863c.067.088-.072.197-.23.315s-.275.201-.342.112c-.066-.088.008-.256.166-.374c.158-.119.34-.142.406-.053");
}

.qe_78ebio {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.557 16.832a3.2 3.2 0 0 1-1.487-.36c-.147-.077-.305.092-.212.229a2.02 2.02 0 0 0 3.397 0c.093-.142-.065-.306-.212-.23c-.43.23-.937.361-1.486.361");
}

.qg7eszk4c {
  stop-color: var(--svg-color--caa48f, #CAA48F);
  stop-opacity: 0;
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qmqoq5wah {
  d: path("M11.658 15.47a1.682 1.682 0 1 0 0-3.363a1.682 1.682 0 0 0 0 3.364");
}

.qpmxtnavh {
  stop-color: var(--svg-color--82604e, #82604E);
  stop-opacity: 0;
}

.qq8pp_7zq {
  stop-color: var(--svg-color--cca490, #CCA490);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy4rrcb8b {
  d: path("M12.857 29.826h-1.578v-8.795a10 10 0 0 1 1.578-.756z");
}

.qzd219blo {
  d: path("M11 8.662a5.773 5.773 0 1 1 11.547 0v1.648H11z");
}

.qzhltkbuo {
  stop-color: var(--svg-color--b9aac8, #B9AAC8);
}

.r0w7kiv9d {
  d: path("M18.84 12.666a.933.933 0 0 1 .899 1.178h-1.802a.937.937 0 0 1 .903-1.179");
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rd7jtnb6n {
  fill: var(--svg-color--000, #000);
  d: path("M18.306 13.598c0-.297.237-.534.534-.534a.532.532 0 0 1 .475.78h-.946a.5.5 0 0 1-.064-.246");
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s3rfzh4ga {
  stop-color: var(--svg-color--a27671, #A27671);
}

.s9u0fjbul {
  stop-color: var(--svg-color--c7a08f, #C7A08F);
  stop-opacity: 0;
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.sbbt-6b7n {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.sjxmvib4j {
  stop-color: var(--svg-color--82604e, #82604E);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.smnqffnel {
  stop-color: var(--svg-color--95646c, #95646C);
  stop-opacity: 0;
}

.sqb-msb-y {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m16.146 13.556l-.714 1.777a.564.564 0 0 0 .544.73h.822a.566.566 0 0 0 .544-.73l-.555-1.777c-.12-.394-.516-.394-.64 0");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.swira1fyd {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.594 2.926");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.th-ps6b7f {
  cx: 13.992px;
  cy: 13.064px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.407px;
  ry: 0.206px;
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tub8lbbfx {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tvoyviyhj {
  stop-color: var(--svg-color--775184, #775184);
}

.twba206ho {
  d: path("M5.963 18.892a.88.88 0 0 0-.37.74v2.108l.618.04h3.302v-2.33c0-.836-.805-1.25-1.97-1.148c-.655.057-1.208.34-1.58.589");
}

.u_34jf9mj {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m20.457 11.452l-.144.24za.28.28 0 0 1-.288.48l-.005-.002l-.022-.013l-.096-.048a3 3 0 0 0-.358-.141a2.4 2.4 0 0 0-1.12-.096a.28.28 0 0 1-.098-.552a2.9 2.9 0 0 1 1.389.114a3.4 3.4 0 0 1 .55.23q.021.011.034.02l.01.005z");
}

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u5bjt8cdp {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.941l.93 1.214c.337.438.519.975.519 1.527l-1.5-.18z");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.u7zreccre {
  d: path("M20.144 20.087a10.2 10.2 0 0 0-3.05-.464h-.641c-.984 0-1.936.14-2.837.4l.608 3.192h4.945z");
}

.uck8wqbzl {
  stop-color: var(--svg-color--9f6f71, #9F6F71);
}

.ucq3z1bcr {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.va-8to-0f {
  stop-color: var(--svg-color--c69985, #C69985);
}

.vcz9qnm9q {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M21.18 8.495h-2.178a.505.505 0 1 1 .08-1.005c.566.09 1.316.215 1.818.34c1.136.281 1.45.834 1.538 1.229a1.58 1.58 0 0 0-1.258-.564");
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4ky7s-1q {
  stop-color: var(--svg-color--ac7b71, #AC7B71);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.w7qmd2b-u {
  d: path("m16.157 13.411l-.556 1.777a.564.564 0 0 0 .544.731h.822a.565.565 0 0 0 .545-.73l-.556-1.778c-.119-.394-.675-.394-.8 0");
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wjchuwb6a {
  stop-color: var(--svg-color--745ba5, #745BA5);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wozepxbaa {
  d: path("M11.048 7.912a6 6 0 0 0-.048.75v1.648h11.547V8.663q0-.381-.049-.75z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wzn2a8b8n {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xnf9zsbcq {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M22.414 19.881a.681.681 0 1 1 1.33-.294l.36 1.794a.645.645 0 0 1-1.26.279z");
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvexp0bjq {
  stop-color: var(--svg-color--895e4d, #895E4D);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y_auwli2s {
  stop-color: var(--svg-color--415e58, #415E58);
}

.y-1rsmdul {
  stop-color: var(--svg-color--3a7ab4, #3A7AB4);
  stop-opacity: 0;
}

.y05rrkbkk {
  stop-color: var(--svg-color--ffff54, #FFFF54);
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yt9en_n3k {
  stop-color: var(--svg-color--9b7368, #9B7368);
  stop-opacity: 0;
}

.yxrzstbma {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.584 11.308c.338-.082 1.176-.041 1.736.36");
}

.z1puarbvc {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.678 14.911a1.123 1.123 0 1 0 0-2.245a1.123 1.123 0 0 0 0 2.245");
}

.z2vq38laf {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.557 16.832a3.2 3.2 0 0 1-1.487-.36c-.147-.077-.305.092-.212.229a2.02 2.02 0 0 0 3.397 0c.093-.142-.065-.306-.212-.23c-.43.23-.937.361-1.486.361Z");
}

.z9e-el7mu {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m19.072 9.417l-1.49.275a.72.72 0 1 1-.13-1.427h2.446c1.448 0 1.927 1.458 1.985 1.957a3.29 3.29 0 0 0-2.811-.805");
}

.zbrgh-b8a {
  d: path("M21.603 14.911a1.123 1.123 0 1 0 0-2.245a1.123 1.123 0 0 0 0 2.245");
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zrsmq2u6o {
  stop-color: var(--svg-color--caa48f, #CAA48F);
}

.zu1-zdlnf {
  d: path("M15.126 13.489c0-.302-.246-.503-.312-.563l-.301.291l.185.378z");
}

</style>
