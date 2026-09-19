<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSrDPqb)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#ij5r3Ic)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i8ltOFb)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iRIUUjc)"><path fill="url(#iObplQb)" class="ggm3_setj"/><path fill="url(#iQpTAtb)" class="ggm3_setj"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#i22XDwd)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#iZyfYcd)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#iG3pHce)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#is9ugbb)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#i52qicc)"><path class="sh7m4tbex"/></g><g filter="url(#isuQ7Xb)"><path class="htooq-bzz"/></g><g filter="url(#iu59PWc)"><path class="dtaunfmfd"/></g><g filter="url(#id7C6nb)"><path class="cz19hw0vg"/></g><g filter="url(#iApxspb)"><path class="h28q1nbvc"/></g><path fill="url(#iaWvCHb)" class="hw860-bkw"/><path fill="url(#iHqXrTb)" class="hw860-bkw"/><path fill="url(#iKOvVob)" class="hw860-bkw"/><g filter="url(#iLDp3tb)"><path fill="url(#iZRDtQc)" class="u5bjt8cdp"/></g><path fill="url(#i5T5fHd)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#itdLitT)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iMq80zd)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#i3YGs4L)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#ihieIdl)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iFQkc1c)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#ioOhupe)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ifr9kzc)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iTt0qwc)" class="twba206ho"/><path fill="url(#i9lIzkb)" class="twba206ho"/><path fill="url(#i8lVEBc)" class="lucypabyc"/><g filter="url(#iEXvsub)"><path class="ndapliy4h"/></g><g filter="url(#ixVunDa)"><path class="spjiriw6x"/></g><g filter="url(#iUg8wTc)"><path class="my0jbbcla"/></g><g filter="url(#ivDiaLE)"><path class="hhnbdw1mn"/></g><g filter="url(#iepk3Wn)"><path stroke="url(#ijG10yh)" class="bdk4dmb5b"/></g><g filter="url(#ixnkBPS)"><path stroke="url(#i9IIrXd)" class="gwm_2mjil"/></g><g filter="url(#iFTpWmb)"><path stroke="url(#i8TsYWd)" class="y2ly1lryk"/></g><g filter="url(#i4AZAwc)"><path stroke="url(#imTyYGd)" class="am6k_ubte"/></g><g filter="url(#irICQ9c)"><path stroke="url(#ikSuYlc)" class="c549xi8ae"/></g><g filter="url(#ijzpU4d)"><circle fill="url(#iIUYQxU)" class="fh9dcj2yc"/></g><g filter="url(#iqPvAfe)"><circle fill="url(#ia78yud)" class="dr-b0bb-i"/></g><g filter="url(#iX56YAb)"><circle fill="url(#i8Jamad)" class="m2z9f7bnh"/><circle fill="url(#iftiYJc)" class="m2z9f7bnh"/></g><g filter="url(#i6MmC4c)"><circle class="sobwi2bhk"/><circle fill="url(#ivYrv8b)" class="n3-23fbtp"/><circle fill="url(#iYwDp4b)" class="n3-23fbtp"/></g><g filter="url(#ilQgild)"><path fill="url(#ikTLpib)" class="gr2njmbak"/><path fill="url(#i2cVq8v)" class="gr2njmbak"/><path fill="url(#imCVzpc)" class="gr2njmbak"/><path fill="url(#iwbyRve)" class="gr2njmbak"/><path fill="url(#iC5sM7c)" class="gr2njmbak"/><path fill="url(#icbKWcd)" class="gr2njmbak"/><path fill="url(#i2m2z4d)" class="gr2njmbak"/></g><g filter="url(#iQ1ju9b)"><path fill="url(#ivYWHLc)" class="ruo9xed4n"/></g><g filter="url(#i31VJKc)"><path class="w6yxp_b8q"/><path fill="url(#ijRu3ac)" class="fgv_66b5h"/><path fill="url(#ilbKHLc)" class="fgv_66b5h"/><path fill="url(#i2uRUKb)" class="fgv_66b5h"/><path fill="url(#iDRsfbb)" class="fgv_66b5h"/></g><g filter="url(#iBBsb7w)"><path class="mkacxibfz"/></g><g filter="url(#iQyOMkN)"><path class="wez-zibyf"/><path fill="url(#i2FW4Ub)" class="vh6te_bmz"/><path fill="url(#i7mM0bh)" class="vh6te_bmz"/><path fill="url(#iXvZTyc)" class="vh6te_bmz"/><path fill="url(#i9eSKrp)" class="vh6te_bmz"/></g><path fill="url(#iP7RGQb)" class="vh6te_bmz"/><path stroke="url(#iRK8tEc)" class="o4pj9ekfe"/><g filter="url(#iGPg8ac)"><path class="apwko0zbg"/></g><g filter="url(#iAupsHb)"><path class="olcbvhbhn"/></g><path class="c5svddcoz"/><path fill="url(#i6dHLId)" class="lrtstf91d"/><path class="all4knbis"/><g filter="url(#inE18bb)"><path class="hlv89izng"/><path fill="url(#i91GpGX)" class="x2x42cjuf"/></g><g filter="url(#i6UEmHc)"><path fill="url(#iQEXBUd)" class="at2w-cb0h"/></g><path class="ut-z-oahc"/><path fill="url(#i3M6DKc)" class="sy7-a8bct"/><path class="ao4br5bwn"/><g filter="url(#iumunxc)"><path fill="url(#iChB28c)" class="r3901acdd"/></g><g filter="url(#idN5A2d)"><ellipse transform="rotate(-27.914 14.176 13.398)" class="ksgt2-bdd"/><ellipse fill="url(#i53PXkc)" transform="rotate(-27.914 14.176 13.398)" class="oggwgcb6y"/></g><g filter="url(#iOBNe9d)"><path stroke="url(#iF518qb)" class="x_sebo8-g"/></g><g filter="url(#ih4aGNb)"><path stroke="url(#itlSCUF)" class="fr10klb9c"/></g><g filter="url(#i8ONlGe)"><path stroke="url(#iVAIyae)" class="d6zsk6l4m"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#iK2GSbd)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iObplQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.266 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="iaWvCHb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="f6slf6w2m"/><stop offset="1" class="p5eexwbyw"/></radialGradient><radialGradient id="iHqXrTb" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="byihu8b7s"/><stop offset="1" class="l1l6vcdra"/></radialGradient><radialGradient id="iKOvVob" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 1.02588 -2.1162 .45124 25.583 20.534)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="nqrf57zsi"/><stop offset="1" class="wrgoaxbaa"/></radialGradient><radialGradient id="iZRDtQc" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="utcasbb3u"/><stop offset="1" class="ww1jp2brw"/></radialGradient><radialGradient id="i5T5fHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="itdLitT" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="iMq80zd" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="i3YGs4L" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="ihieIdl" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="iFQkc1c" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="ioOhupe" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="ifr9kzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="iTt0qwc" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="sheftacio"/><stop offset=".644" class="vbn8f2bra"/></radialGradient><radialGradient id="i9lIzkb" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="khemg5bhx"/><stop offset="1" class="e7777ub0x"/></radialGradient><radialGradient id="i8lVEBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.24809 -2.56376 1.92445 16.098 20.289)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="cg9m3ci5c"/><stop offset="1" class="ux87x8bpy"/></radialGradient><radialGradient id="iIUYQxU" cx="0" cy="0" r="1" gradientTransform="matrix(1.84203 0 0 3.22356 10.018 14.214)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iftiYJc" cx="0" cy="0" r="1" gradientTransform="matrix(.86777 -.63186 .72119 .99044 22.146 13.936)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ivYrv8b" cx="0" cy="0" r="1" gradientTransform="matrix(.86205 -1.58556 .92803 .50456 21.712 15.076)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iYwDp4b" cx="0" cy="0" r="1" gradientTransform="matrix(.27217 .2694 -.3473 .35086 21.756 14.214)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="i2cVq8v" cx="0" cy="0" r="1" gradientTransform="scale(12.2089 8.99403)rotate(90 .01 1.365)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="ijcd4zbii"/><stop offset="1" class="ci63ols4m"/></radialGradient><radialGradient id="iC5sM7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.372 1.68862 0 19.216 12.88)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="icbKWcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45995 1.81558 0 14.432 12.844)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ijRu3ac" cx="0" cy="0" r="1" gradientTransform="matrix(.83744 -3.10348 1.15087 .31055 21.315 9.905)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ilbKHLc" cx="0" cy="0" r="1" gradientTransform="matrix(4.01482 .36946 -.19866 2.15874 19.59 8.057)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i2uRUKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.76258 -2.72974 0 16.754 5.186)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iDRsfbb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 23.853 -9.087)scale(4.00028 6.26713)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i9eSKrp" cx="0" cy="0" r="1" gradientTransform="matrix(0 .20668 -.66401 0 17.097 15.9)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="i6dHLId" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85142 -1.35428 0 19.04 13.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i91GpGX" cx="0" cy="0" r="1" gradientTransform="matrix(-.24338 -.31363 .4318 -.33508 18.801 13.586)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3M6DKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85146 -1.35435 0 14.461 13.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i53PXkc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.838 -.106)scale(.51857 .62334)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="iK2GSbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.268 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="iSrDPqb" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="ij5r3Ic" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23860"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23860" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23860"/></filter><filter id="i8ltOFb" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23860"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23860" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23860"/></filter><filter id="iRIUUjc" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="i22XDwd" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".5"/></filter><filter id="iZyfYcd" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iG3pHce" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="is9ugbb" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="i52qicc" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.67451 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="isuQ7Xb" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iu59PWc" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="id7C6nb" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iApxspb" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iLDp3tb" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.662745 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iEXvsub" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="ixVunDa" width="1.286" height="2.978" x="23.932" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="iUg8wTc" width="1.444" height="3.775" x="24.962" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="ivDiaLE" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="iepk3Wn" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="ixnkBPS" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="iFTpWmb" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="i4AZAwc" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="irICQ9c" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="ijzpU4d" width="3.705" height="3.505" x="10.018" y="12.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iqPvAfe" width="3.089" height="3.089" x="10.226" y="12.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".25"/></filter><filter id="iX56YAb" width="3.755" height="3.755" x="20.003" y="12.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="i6MmC4c" width="3.089" height="3.089" x="20.211" y="12.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".25"/></filter><filter id="ilQgild" width="10.889" height="12.875" x="11.339" y="8.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iQ1ju9b" width="8.457" height="7.219" x="14.932" y="6.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation="1"/></filter><filter id="i31VJKc" width="13.211" height="8.943" x="10.144" y="4.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iBBsb7w" width="3.347" height="4.314" x="14.829" y="13.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".375"/></filter><filter id="iQyOMkN" width="2.47" height="3.314" x="15.518" y="13.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><filter id="iGPg8ac" width="3.115" height="1.946" x="17.994" y="10.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="iAupsHb" width="3.115" height="1.946" x="12.591" y="10.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23860"/></filter><filter id="inE18bb" width=".816" height=".721" x="18.275" y="13.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".05"/></filter><filter id="i6UEmHc" width=".916" height=".939" x="19.162" y="13.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".1"/></filter><filter id="iumunxc" width="1.015" height="1.072" x="14.499" y="13.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".1"/></filter><filter id="idN5A2d" width=".948" height=".729" x="13.702" y="13.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".05"/></filter><filter id="iOBNe9d" width="3.191" height="1.702" x="17.871" y="10.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".25"/></filter><filter id="ih4aGNb" width="3.273" height="1.762" x="12.393" y="10.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".25"/></filter><filter id="i8ONlGe" width="1.021" height="2.345" x="11.35" y="8.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23860" stdDeviation=".125"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="ijG10yh" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="i3-_-w2pf"/><stop offset="1" class="nntb9stew"/><stop offset="1" class="hyql_fbqw"/></linearGradient><linearGradient id="i9IIrXd" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="i8TsYWd" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="imTyYGd" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="ikSuYlc" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="ia78yud" x1="11.77" x2="11.098" y1="14.506" y2="14.506" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="i8Jamad" x1="22.896" x2="22.037" y1="13.068" y2="15.73" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ikTLpib" x1="20.99" x2="12.974" y1="14.623" y2="15.817" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="imCVzpc" x1="10.831" x2="14.356" y1="16.226" y2="16.346" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iwbyRve" x1="11.09" x2="13.065" y1="17.453" y2="17.382" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="i2m2z4d" x1="16.784" x2="16.784" y1="10.451" y2="11.889" gradientUnits="userSpaceOnUse"><stop offset=".228" class="g91s4fbit"/><stop offset="1" class="v-1xbsyeb"/></linearGradient><linearGradient id="ivYWHLc" x1="16.195" x2="24.744" y1="11.49" y2="8.429" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="i2FW4Ub" x1="15.846" x2="16.831" y1="15.315" y2="15.315" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="i7mM0bh" x1="17.738" x2="16.662" y1="15.653" y2="15.638" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iXvZTyc" x1="16.958" x2="16.958" y1="16.433" y2="15.831" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iP7RGQb" x1="16.885" x2="16.885" y1="16.477" y2="16.301" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iRK8tEc" x1="15.665" x2="16.122" y1="18.128" y2="17.406" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iQEXBUd" x1="19.857" x2="19.528" y1="13.555" y2="13.758" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iChB28c" x1="15.242" x2="14.912" y1="13.555" y2="13.758" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iF518qb" x1="19.873" x2="19.432" y1="11.309" y2="10.408" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="itlSCUF" x1="14.306" x2="13.057" y1="11.175" y2="10.651" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iVAIyae" x1="11.86" x2="11.86" y1="9.06" y2="11.324" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-juggling-light" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.all4knbis {
  fill: var(--svg-color--000, #000);
  d: path("M18.506 13.934c0-.298.239-.536.537-.536a.534.534 0 0 1 .476.783h-.949a.5.5 0 0 1-.064-.247");
}

.am6k_ubte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.981 17.139c.11.172.625 1.078 1.282 1.273");
}

.ao4br5bwn {
  fill: var(--svg-color--000, #000);
  d: path("M14.995 13.934a.534.534 0 0 0-.536-.536a.534.534 0 0 0-.477.783h.95a.5.5 0 0 0 .063-.247");
}

.apwko0zbg {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m20.658 11.359l-.001-.001l-.002-.002l-.005-.004l-.013-.01a2 2 0 0 0-.162-.113a2.7 2.7 0 0 0-.44-.22a3 3 0 0 0-1.568-.167a.56.56 0 1 0 .175 1.107c.418-.066.752.01.98.101a1.6 1.6 0 0 1 .316.168l.008.006a.56.56 0 0 0 .712-.865");
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.at2w-cb0h {
  d: path("M19.877 13.81a.9.9 0 0 0-.243-.485l-.272.3l.123.239z");
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
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

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.byihu8b7s {
  stop-color: var(--svg-color--dba096, #DBA096);
  stop-opacity: 0;
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c549xi8ae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.77 17.467c.177.245.618 1.078 1.72 1.594");
}

.c5svddcoz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.26 12.712c.685 0 1.264.473 1.422 1.111a.288.288 0 0 1-.281.358h-2.342a.242.242 0 0 1-.238-.285a1.47 1.47 0 0 1 1.439-1.184");
}

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.cg9m3ci5c {
  stop-color: var(--svg-color--c57e83, #C57E83);
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ci63ols4m {
  stop-color: var(--svg-color--bd7c8b, #BD7C8B);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.cz19hw0vg {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d6zsk6l4m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.995 9.164v.942c-.008.156-.073.505-.27.652");
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

.dr-b0bb-i {
  cx: 11.77px;
  cy: 14.214px;
  r: 1.044px;
}

.dtaunfmfd {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.dzgp29byh {
  stop-color: var(--svg-color--ffd0bd, #FFD0BD);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7777ub0x {
  stop-color: var(--svg-color--ebb8a2, #EBB8A2);
  stop-opacity: 0;
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f6slf6w2m {
  stop-color: var(--svg-color--ffd3be, #FFD3BE);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fgv_66b5h {
  d: path("m21.812 7.415l.118 1.903c.789.392 1.571-.392 1.402.56l-.62 3.19c-.054.33-.272.552-.6.56h-.018s.056-.951.112-1.51c.046-.456-.034-.594-.45-1.009c-.225-.224-.394-.56-.394-.895v-.896c0-.28-.226-.504-.45-.56c-.676-.168-2.084-.448-4.111-.448s-3.434.28-4.11.448a.546.546 0 0 0-.45.56v.896c0 .335-.113.671-.395.895l-.169.168c-.225.168-.337.504-.337.784c.056.616.112 1.512.112 1.512l-.051-.002a.665.665 0 0 1-.624-.558l-.62-3.191c-.112-.896.507.256 1.295-.136l.282-2.271a8 8 0 0 0 .844-.616l1.014-1.064c.62-.56 1.52-.728 2.308-.336a3.1 3.1 0 0 0 1.746 0c.844-.28 1.801-.056 2.477.56l.845.84c.225.28.506.448.844.616");
}

.fh9dcj2yc {
  cx: 11.77px;
  cy: 14.214px;
  r: 1.752px;
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.fr10klb9c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.018 11.751c.343-.303 1.093-.623 2.023-.475");
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.g91s4fbit {
  stop-color: var(--svg-color--d1968a, #D1968A);
}

.g9xx7math {
  stop-color: var(--svg-color--e7aea1, #E7AEA1);
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ggm3_setj {
  d: path("m13.38 20.005l.612 3.22h4.946l.796-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.894.133-2.777.382");
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gr2njmbak {
  d: path("M11.34 12.06c0-.279.112-.615.337-.783l.169-.168c.281-.224.394-.56.394-.896v-.895c0-.28.169-.504.45-.56c.676-.168 2.084-.448 4.11-.448c2.028 0 3.435.28 4.11.448c.226.056.451.28.451.56v.896c0 .335.17.671.394.895c.527.37.495.573.45 1.008c-.055.56-.112 1.511-.112 1.511h.02l-.28 4.155c-.168 1.858-1.629 3.152-3.37 3.152h-3.37c-1.797 0-3.2-1.294-3.37-3.152c-.146-1.906-.21-3.819-.384-5.722");
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

.h28q1nbvc {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hhnbdw1mn {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hlv89izng {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.974 13.196c.067.089-.073.198-.232.316c-.158.119-.276.202-.343.113c-.066-.09.008-.258.167-.376c.158-.119.341-.143.408-.053");
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.htooq-bzz {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hyql_fbqw {
  stop-color: var(--svg-color--ffd5bf, #FFD5BF);
  stop-opacity: 0;
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i3-_-w2pf {
  stop-color: var(--svg-color--ffd5bf, #FFD5BF);
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

.ijcd4zbii {
  stop-color: var(--svg-color--d59b9c, #D59B9C);
  stop-opacity: 0;
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jzs0qy57r {
  stop-color: var(--svg-color--f9c6ac, #F9C6AC);
}

.khemg5bhx {
  stop-color: var(--svg-color--dea98d, #DEA98D);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.ksgt2-bdd {
  cx: 14.176px;
  cy: 13.398px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
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

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l1l6vcdra {
  stop-color: var(--svg-color--dba096, #DBA096);
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

.lrtstf91d {
  d: path("M19.043 12.998a.937.937 0 0 1 .902 1.183h-1.809a.94.94 0 0 1 .907-1.183");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lucypabyc {
  d: path("M14.545 18.417c0-.99.9-1.794 2.011-1.794s2.012.803 2.012 1.794v2.326c0 .99-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m2z9f7bnh {
  cx: 21.756px;
  cy: 14.214px;
  r: 1.752px;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
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

.mkacxibfz {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m16.465 14.086l-.862 1.784c-.106.367.15.734.513.734h.774c.363 0 .619-.373.512-.734l-.523-1.784c-.112-.395-.297-.395-.415 0");
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.my0jbbcla {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.593 2.926");
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.n3-23fbtp {
  cx: 21.756px;
  cy: 14.214px;
  r: 1.044px;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ndapliy4h {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nntb9stew {
  stop-color: var(--svg-color--efc0a4, #EFC0A4);
  stop-opacity: 0;
}

.nqrf57zsi {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o4pj9ekfe {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.323 17.11c.413.216.906.34 1.43.34c.53 0 1.018-.124 1.431-.34a.21.21 0 0 1 .251.041c.06.062.081.161.022.25m-3.134-.29l3.092.263m-3.092-.264a.21.21 0 0 0-.252.044a.194.194 0 0 0-.02.248m.272-.292l-.231.264m3.365.028l-.042-.028m.042.028l-.042-.028m.042.028c-.36.546-.989.91-1.704.91a2.04 2.04 0 0 1-1.703-.91m3.365-.028a1.99 1.99 0 0 1-1.662.888c-.697 0-1.31-.355-1.661-.888m-.042.028l.042-.028m-.042.028l.042-.028");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oggwgcb6y {
  cx: 14.176px;
  cy: 13.398px;
  rx: 0.409px;
  ry: 0.207px;
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

.olcbvhbhn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.793 11.36v-.002h.002l.001-.002l.005-.004l.013-.01a2 2 0 0 1 .162-.113a2.7 2.7 0 0 1 .44-.22a3 3 0 0 1 1.568-.167a.56.56 0 1 1-.175 1.107a1.85 1.85 0 0 0-.98.101a1.6 1.6 0 0 0-.315.168l-.009.006a.56.56 0 0 1-.712-.865");
}

.p5eexwbyw {
  stop-color: var(--svg-color--edb9a9, #EDB9A9);
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

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
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

.r3901acdd {
  d: path("M15.314 13.824c0-.303-.246-.504-.312-.565l-.303.293l.186.379z");
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.ruo9xed4n {
  d: path("m20.914 8.31l-3.23 1.077a1.1 1.1 0 0 0 .493 2.132l3.212-.43z");
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.sh7m4tbex {
  fill: var(--svg-color--ffd4bf, #FFD4BF);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sobwi2bhk {
  cx: 21.756px;
  cy: 14.214px;
  r: 1.044px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.spjiriw6x {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.357 18.55l.437 2.127");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.sy7-a8bct {
  d: path("M14.459 12.998a.937.937 0 0 0-.903 1.183h1.81a1 1 0 0 0 .034-.247a.943.943 0 0 0-.941-.936");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tub8lbbfx {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
}

.tvoyviyhj {
  stop-color: var(--svg-color--775184, #775184);
}

.twba206ho {
  d: path("M5.963 18.892a.88.88 0 0 0-.37.74v2.108l.618.04h3.302v-2.33c0-.836-.805-1.25-1.97-1.148c-.655.057-1.208.34-1.58.589");
}

.txbqaun0d {
  stop-color: var(--svg-color--d39891, #D39891);
  stop-opacity: 0;
}

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u5bjt8cdp {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.941l.93 1.214c.337.438.519.975.519 1.527l-1.5-.18z");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ut-z-oahc {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.241 12.712c-.685 0-1.264.473-1.421 1.112a.288.288 0 0 0 .28.357h2.342a.242.242 0 0 0 .238-.285a1.47 1.47 0 0 0-1.439-1.184");
}

.utcasbb3u {
  stop-color: var(--svg-color--f3c0a7, #F3C0A7);
}

.ux87x8bpy {
  stop-color: var(--svg-color--e2aa9f, #E2AA9F);
}

.v-1xbsyeb {
  stop-color: var(--svg-color--d1968a, #D1968A);
  stop-opacity: 0;
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.vbn8f2bra {
  stop-color: var(--svg-color--f0bea2, #F0BEA2);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vh6te_bmz {
  d: path("m16.352 13.915l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.557-1.784c-.12-.396-.678-.396-.803 0");
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.w5mx_ioxz {
  stop-color: var(--svg-color--ffd0bd, #FFD0BD);
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.w6yxp_b8q {
  fill: var(--svg-color--242324, #242324);
  d: path("m21.812 7.415l.118 1.903c.789.392 1.571-.392 1.402.56l-.62 3.19c-.054.33-.272.552-.6.56h-.018s.056-.951.112-1.51c.046-.456-.034-.594-.45-1.009c-.225-.224-.394-.56-.394-.895v-.896c0-.28-.226-.504-.45-.56c-.676-.168-2.084-.448-4.111-.448s-3.434.28-4.11.448a.546.546 0 0 0-.45.56v.896c0 .335-.113.671-.395.895l-.169.168c-.225.168-.337.504-.337.784c.056.616.112 1.512.112 1.512l-.051-.002a.665.665 0 0 1-.624-.558l-.62-3.191c-.112-.896.507.256 1.295-.136l.282-2.271a8 8 0 0 0 .844-.616l1.014-1.064c.62-.56 1.52-.728 2.308-.336a3.1 3.1 0 0 0 1.746 0c.844-.28 1.801-.056 2.477.56l.845.84c.225.28.506.448.844.616");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wez-zibyf {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m16.352 13.915l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.557-1.784c-.12-.396-.678-.396-.803 0");
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wjchuwb6a {
  stop-color: var(--svg-color--745ba5, #745BA5);
  stop-opacity: 0;
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wozepxbaa {
  d: path("M11.048 7.912a6 6 0 0 0-.048.75v1.648h11.547V8.663q0-.381-.049-.75z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wrgoaxbaa {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
  stop-opacity: 0;
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.ww1jp2brw {
  stop-color: var(--svg-color--ebae91, #EBAE91);
}

.x_sebo8-g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.497 11.207c.45-.079 1.331-.056 1.94.418");
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x2x42cjuf {
  d: path("M18.974 13.196c.067.089-.073.198-.232.316c-.158.119-.276.202-.343.113c-.066-.09.008-.258.167-.376c.158-.119.341-.143.408-.053");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xm9fbaccy {
  stop-color: var(--svg-color--d39891, #D39891);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
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

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
