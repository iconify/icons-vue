<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#il1tuId)" class="m7q-jebcz"/><path fill="url(#iQ2jLze)" class="m7q-jebcz"/><g filter="url(#iUacqMd)"><path class="in4zu5bby"/></g><g filter="url(#imwSeka)"><path class="qaic2qhdc"/></g><path fill="url(#iBwb0oW)" class="wumwldbiq"/><path fill="url(#iJHAOCB)" class="wumwldbiq"/><path fill="url(#iFI7VEG)" class="wumwldbiq"/><path fill="url(#iy7k0SA)" class="k23prac0f"/><path fill="url(#iejpjIb)" class="k23prac0f"/><g filter="url(#idLStHe)"><path fill="url(#ik2hrRd)" class="hsl_9pnjq"/><path fill="url(#ih5b6TI)" class="hsl_9pnjq"/><path fill="url(#ikFi6Ud)" class="hsl_9pnjq"/></g><path fill="url(#iA9W8hc)" class="hsl_9pnjq"/><path fill="url(#iixVMne)" class="hsl_9pnjq"/><path fill="url(#iEEG0Rb)" class="hsl_9pnjq"/><g filter="url(#ikPdDvz)"><path fill="url(#iJ6Y3Gc)" class="hf0gbe--z"/></g><g filter="url(#iZT2NGd)"><path class="wdhdhpbgf"/><path fill="url(#iVO0Mpu)" class="wb41v0bdx"/></g><path fill="url(#iW0JkNb)" class="a994tbbjq"/><path fill="url(#inaBuTd)" class="a994tbbjq"/><path fill="url(#iwMrNnb)" class="wlgaofbce"/><path fill="url(#iARIzte)" class="jl3cs8-ek"/><path fill="url(#iKXW4mb)" class="jl3cs8-ek"/><path fill="url(#iyYmlfc)" class="jl3cs8-ek"/><path fill="url(#iMLj1Wb)" class="q6ugjac7p"/><g filter="url(#i7Yyicj)"><circle fill="url(#iPFnjed)" class="x4d85ybrc"/></g><g filter="url(#iabAX8d)"><circle fill="url(#isJpQGY)" class="lnokdwb4h"/></g><g filter="url(#iikSeUd)"><circle fill="url(#iGoXdXb)" class="aerzurb7x"/><circle fill="url(#iG2ahgb)" class="aerzurb7x"/></g><g filter="url(#iewMZie)"><circle class="soot7zb-j"/><circle fill="url(#ieYLxic)" class="fw4ec32jp"/><circle fill="url(#iDgM9oc)" class="fw4ec32jp"/></g><g filter="url(#iK2Es6c)"><path fill="url(#iH56Fnd)" class="k96ld9eeh"/><path fill="url(#idhB0ze)" class="k96ld9eeh"/><path fill="url(#ih7th8c)" class="k96ld9eeh"/><path fill="url(#iZbFwHd)" class="k96ld9eeh"/><path fill="url(#ibEDW8b)" class="k96ld9eeh"/></g><g filter="url(#ikNMold)"><path class="mwhb50b1t"/><path fill="url(#ibxHD2b)" class="bmckutbjr"/><path fill="url(#is28dHb)" class="bmckutbjr"/><path fill="url(#iJV46Ib)" class="bmckutbjr"/><path fill="url(#ikUKI7c)" class="bmckutbjr"/><path fill="url(#icyYT2d)" class="bmckutbjr"/></g><path fill="url(#iMhzP2b)" class="bmckutbjr"/><path fill="url(#ic6ilEc)" class="bmckutbjr"/><g filter="url(#iwNqMKi)"><path class="ghr25ab2n"/></g><g filter="url(#irNRHPe)"><path class="qifnvjwdt"/><path fill="url(#i1rjGNH)" class="zg3sctqig"/><path fill="url(#i6xcX9d)" class="zg3sctqig"/><path fill="url(#itDUV6c)" class="zg3sctqig"/></g><path fill="url(#iPSjkub)" class="zg3sctqig"/><path stroke="url(#iGn8YUP)" class="zfwdzhtah"/><g filter="url(#ilpNLye)"><path class="g-8x7ac0x"/></g><g filter="url(#iBUTxSb)"><path class="wus418bat"/></g><path class="vdn__nyab"/><path fill="url(#i4WvwTb)" class="q_52qxbtx"/><path class="a3s4sgjpc"/><g filter="url(#ilG1gCc)"><path class="gcpne9bss"/><path fill="url(#ixZ9eHe)" class="h0wr0xfvz"/></g><g filter="url(#iUOnpJb)"><path fill="url(#iZH8Ead)" class="gaf_tniss"/></g><path class="pfz0l_83h"/><path fill="url(#ibUoDje)" class="cms-qvblc"/><path class="re9rfs4ln"/><g filter="url(#iuAZiQe)"><path fill="url(#i8d8Sdq)" class="yse58cb3o"/></g><g filter="url(#iVQFvnb)"><ellipse transform="rotate(-27.914 13.521 9.853)" class="qb3uiab3z"/><ellipse fill="url(#iZyIBod)" transform="rotate(-27.914 13.521 9.853)" class="hb_2j5bjc"/></g><g filter="url(#i95ytMb)"><path stroke="url(#i9sVGQd)" class="zpwemrbdg"/></g><g filter="url(#ixNCTLo)"><path stroke="url(#iGfve0c)" class="oaftwmbuh"/></g><defs><linearGradient id="il1tuId" x1="16" x2="16" y1="16.271" y2="31.208" gradientUnits="userSpaceOnUse"><stop class="aj_3f3bsc"/><stop offset="1" class="wnr_hxb1w"/></linearGradient><linearGradient id="iJHAOCB" x1="18.903" x2="17.059" y1="25.271" y2="25.271" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="iFI7VEG" x1="15.591" x2="15.669" y1="17.818" y2="21.708" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="iejpjIb" x1="23" x2="23.744" y1="29.446" y2="29.422" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="ik2hrRd" x1="11.902" x2="11.902" y1="16.049" y2="29.949" gradientUnits="userSpaceOnUse"><stop class="f3sse8oum"/><stop offset=".524" class="u_3z34bhk"/></linearGradient><linearGradient id="ih5b6TI" x1="13.671" x2="13.05" y1="22.509" y2="22.509" gradientUnits="userSpaceOnUse"><stop class="ihv8a_ggy"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iA9W8hc" x1="11.902" x2="12.839" y1="25.925" y2="25.524" gradientUnits="userSpaceOnUse"><stop offset=".196" class="k61ntrncu"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iEEG0Rb" x1="12.223" x2="12.434" y1="16.049" y2="16.451" gradientUnits="userSpaceOnUse"><stop class="po-lo7b_p"/><stop offset="1" class="un5vu3b4v"/></linearGradient><linearGradient id="iJ6Y3Gc" x1="15.988" x2="15.988" y1="18.943" y2="20.927" gradientUnits="userSpaceOnUse"><stop offset=".006" class="cv8mglbzi"/><stop offset="1" class="s7ujjhbeb"/></linearGradient><linearGradient id="iVO0Mpu" x1="18.71" x2="20.111" y1="21.556" y2="21.556" gradientUnits="userSpaceOnUse"><stop offset=".093" class="d4aenlb5d"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iwMrNnb" x1="9.452" x2="7.02" y1="23.967" y2="23.967" gradientUnits="userSpaceOnUse"><stop class="qv0c6ccxx"/><stop offset="1" class="ox2qw0bwk"/></linearGradient><linearGradient id="iKXW4mb" x1="14.606" x2="14.899" y1="24.829" y2="24.869" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iyYmlfc" x1="17.411" x2="17.012" y1="24.646" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="isJpQGY" x1="11.229" x2="10.588" y1="10.91" y2="10.91" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iGoXdXb" x1="21.828" x2="21.009" y1="9.54" y2="12.076" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iH56Fnd" x1="20.012" x2="12.376" y1="11.021" y2="12.158" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ih7th8c" x1="10.581" x2="12.893" y1="13.716" y2="13.415" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="is28dHb" x1="11.116" x2="14.017" y1="10.364" y2="5.21" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="i1rjGNH" x1="15.112" x2="16.05" y1="11.68" y2="11.68" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="i6xcX9d" x1="16.915" x2="15.889" y1="12.002" y2="11.988" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="itDUV6c" x1="16.171" x2="16.171" y1="12.744" y2="12.171" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iPSjkub" x1="16.102" x2="16.102" y1="12.786" y2="12.619" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iGn8YUP" x1="14.939" x2="15.374" y1="14.36" y2="13.672" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iZH8Ead" x1="18.933" x2="18.619" y1="10.003" y2="10.196" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8d8Sdq" x1="14.536" x2="14.222" y1="10.003" y2="10.196" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9sVGQd" x1="18.948" x2="18.528" y1="7.864" y2="7.005" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iGfve0c" x1="13.644" x2="12.455" y1="7.736" y2="7.237" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><radialGradient id="iQ2jLze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.452)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="iBwb0oW" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 23.024)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iy7k0SA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.96)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="ikFi6Ud" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.713 11.647)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="i1uneh2yx"/><stop offset="1" class="iw5474bga"/></radialGradient><radialGradient id="iixVMne" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15358 .53752 11.395 19.716)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="iW0JkNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.474)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="zr8leoe3h"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="inaBuTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.971)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="po0u5abxc"/><stop offset=".876" class="s80u955fl"/></radialGradient><radialGradient id="iARIzte" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.983 21.365)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ium-0_blv"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iMLj1Wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89252 -2.87161 0 16.03 17.22)" gradientUnits="userSpaceOnUse"><stop offset=".414" class="qp_mkdtgr"/><stop offset="1" class="hk55svsak"/></radialGradient><radialGradient id="iPFnjed" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.56 10.631)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iG2ahgb" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.113 10.366)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="ieYLxic" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.7 11.452)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iDgM9oc" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.741 10.632)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="idhB0ze" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0105 -18.8206 0 16.447 7.29)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="r74fglq0r"/><stop offset=".978" class="tgyaulyub"/></radialGradient><radialGradient id="iZbFwHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.322 9.36)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ibEDW8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.764 9.326)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ibxHD2b" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.12 6.276)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iJV46Ib" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.783 7.176)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="ikUKI7c" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.203 8.894)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="icyYT2d" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.2 2.03)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iMhzP2b" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.671 2.03)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="ic6ilEc" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.631 3.759)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i4WvwTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.155 10.283)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixZ9eHe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.42 .627)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibUoDje" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.792 10.283)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iZyIBod" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.758 -1.564)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iUacqMd" width="6.556" height="14.595" x="9.212" y="15.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".5"/></filter><filter id="imwSeka" width="3.95" height="13.362" x="17.96" y="16.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".375"/></filter><filter id="idLStHe" width="2.897" height="14" x="10.503" y="16.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="ikPdDvz" width="2.965" height="2.883" x="14.509" y="18.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2104" result="effect2_innerShadow_4002_2104"/></filter><filter id="iZT2NGd" width="2.902" height="14.05" x="18.61" y="15.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="i7Yyicj" width="3.539" height="3.339" x="9.559" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="iabAX8d" width="2.99" height="2.99" x="9.734" y="9.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".25"/></filter><filter id="iikSeUd" width="3.589" height="3.589" x="19.072" y="8.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="iewMZie" width="2.99" height="2.99" x="19.246" y="9.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".25"/></filter><filter id="iK2Es6c" width="10.373" height="12.177" x="10.819" y="5.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="ikNMold" width="12.601" height="8.543" x="9.676" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="iwNqMKi" width="3.26" height="4.181" x="14.107" y="9.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".375"/></filter><filter id="irNRHPe" width="2.377" height="3.181" x="14.788" y="9.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".125"/></filter><filter id="ilpNLye" width="2.979" height="1.873" x="17.158" y="6.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="iBUTxSb" width="2.98" height="1.873" x="12.011" y="6.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2104"/></filter><filter id="ilG1gCc" width=".787" height=".696" x="17.421" y="9.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".05"/></filter><filter id="iUOnpJb" width=".891" height=".913" x="18.261" y="9.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".1"/></filter><filter id="iuAZiQe" width=".986" height="1.04" x="13.819" y="9.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".1"/></filter><filter id="iVQFvnb" width=".913" height=".704" x="13.065" y="9.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".05"/></filter><filter id="i95ytMb" width="3.099" height="1.681" x="17.012" y="7.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".25"/></filter><filter id="ixNCTLo" width="3.177" height="1.738" x="11.793" y="7.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2104" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-office-worker-medium-light" /></template>
<style>
.a3s4sgjpc {
  fill: var(--svg-color--000, #000);
  d: path("M17.646 10.365c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.a994tbbjq {
  d: path("M16 15.016h-2.71v4.74c0 .31.36.49.61.29l2.1-1.392l2.1 1.392c.25.2.61.02.61-.29v-4.74z");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aerzurb7x {
  cx: 20.741px;
  cy: 10.631px;
  r: 1.669px;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.aj_3f3bsc {
  stop-color: var(--svg-color--594e72, #594E72);
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bmckutbjr {
  d: path("m20.795 4.154l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.535-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cms-qvblc {
  d: path("M13.79 9.472a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.cv8mglbzi {
  stop-color: var(--svg-color--5a3859, #5A3859);
}

.d4aenlb5d {
  stop-color: var(--svg-color--5a4c74, #5A4C74);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f3sse8oum {
  stop-color: var(--svg-color--594b78, #594B78);
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.fw4ec32jp {
  cx: 20.741px;
  cy: 10.631px;
  r: 0.995px;
}

.g-8x7ac0x {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M19.696 7.911h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.054c.398-.062.716.011.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gaf_tniss {
  d: path("M18.952 10.247a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.gcpne9bss {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.091 9.66c.064.086-.069.19-.22.303s-.263.192-.327.107c-.063-.085.008-.246.159-.358c.15-.113.325-.136.388-.051");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghr25ab2n {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.701 10.509l-.82 1.7c-.102.349.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h0wr0xfvz {
  d: path("M18.091 9.66c.064.086-.069.19-.22.303s-.263.192-.327.107c-.063-.085.008-.246.159-.358c.15-.113.325-.136.388-.051");
}

.hb_2j5bjc {
  cx: 13.521px;
  cy: 9.853px;
  rx: 0.389px;
  ry: 0.197px;
}

.hf0gbe--z {
  d: path("m16.013 18.286l-1.357 1.275a.15.15 0 0 0-.031.177l.596 1.193a.25.25 0 0 0 .224.138h1.09a.25.25 0 0 0 .224-.14l.6-1.212a.15.15 0 0 0-.032-.175z");
}

.hk55svsak {
  stop-color: var(--svg-color--894f50, #894F50);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hsl_9pnjq {
  d: path("M13.29 16.05h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i1uneh2yx {
  stop-color: var(--svg-color--4e3360, #4E3360);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.ihv8a_ggy {
  stop-color: var(--svg-color--553a63, #553A63);
}

.in4zu5bby {
  fill: var(--svg-color--46375f, #46375F);
  d: path("M13.419 16.808c-.513 0-1.296-.029-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.ium-0_blv {
  stop-color: var(--svg-color--59416d, #59416D);
}

.iw5474bga {
  stop-color: var(--svg-color--4e3360, #4E3360);
  stop-opacity: 0;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jl3cs8-ek {
  d: path("M15.505 21.07a.25.25 0 0 0-.248.212l-1.327 8.667h4.11l-1.318-8.667a.25.25 0 0 0-.247-.213z");
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k23prac0f {
  d: path("M23 17.977V29.96h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.k61ntrncu {
  stop-color: var(--svg-color--594c7d, #594C7D);
}

.k96ld9eeh {
  d: path("m10.877 10.018l.049.002s-.054-.853-.107-1.44c0-.266.107-.586.321-.746l.161-.16c.268-.214.376-.534.376-.854v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.854c.502.351.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnokdwb4h {
  cx: 11.229px;
  cy: 10.631px;
  r: 0.995px;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.m7q-jebcz {
  d: path("M16 15.46c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mwhb50b1t {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.795 4.154l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.535-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.oaftwmbuh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.418 8.285c.327-.289 1.041-.593 1.927-.452");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.ox2qw0bwk {
  stop-color: var(--svg-color--43395f, #43395F);
  stop-opacity: 0;
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pfz0l_83h {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.583 9.2c-.652 0-1.204.45-1.354 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.po-lo7b_p {
  stop-color: var(--svg-color--584360, #584360);
}

.po0u5abxc {
  stop-color: var(--svg-color--9d8392, #9D8392);
  stop-opacity: 0;
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.q_52qxbtx {
  d: path("M18.157 9.472a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.q6ugjac7p {
  d: path("M14.045 16.849c.02.213.205.69.746 1.055c.213.143 1.213.628 1.193.618c.156-.078.807-.298 1.284-.618c.54-.364.725-.842.746-1.055l-1.985-.953z");
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qaic2qhdc {
  fill: var(--svg-color--493e6a, #493E6A);
  d: path("m20.905 21.14l-1.19-.827a.23.23 0 0 1 .166-.394h.919a.252.252 0 0 0 .227-.358l-1.076-2.29a8 8 0 0 0-.646-.237h-.595v11.862l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.qb3uiab3z {
  cx: 13.521px;
  cy: 9.853px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.qifnvjwdt {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.594 10.346l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.qp_mkdtgr {
  stop-color: var(--svg-color--ac7272, #AC7272);
}

.qv0c6ccxx {
  stop-color: var(--svg-color--43395f, #43395F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r74fglq0r {
  stop-color: var(--svg-color--bd7a87, #BD7A87);
  stop-opacity: 0;
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.re9rfs4ln {
  fill: var(--svg-color--000, #000);
  d: path("M14.301 10.365a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.s7ujjhbeb {
  stop-color: var(--svg-color--463952, #463952);
}

.s80u955fl {
  stop-color: var(--svg-color--815a72, #815A72);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.soot7zb-j {
  cx: 20.741px;
  cy: 10.631px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.tgyaulyub {
  stop-color: var(--svg-color--ab6386, #AB6386);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u_3z34bhk {
  stop-color: var(--svg-color--5d5087, #5D5087);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.un5vu3b4v {
  stop-color: var(--svg-color--584360, #584360);
  stop-opacity: 0;
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vdn__nyab {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.364 9.2c.653 0 1.204.45 1.354 1.06a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.37-1.127");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wb41v0bdx {
  d: path("m21.22 21.08l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.wdhdhpbgf {
  fill: var(--svg-color--615990, #615990);
  d: path("m21.22 21.08l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wlgaofbce {
  d: path("M7.032 29.96H8.97V17.994a11 11 0 0 0-3.656 5.843a11 11 0 0 0-.304 2.631l.02 3.49z");
}

.wnr_hxb1w {
  stop-color: var(--svg-color--594984, #594984);
}

.wumwldbiq {
  d: path("M18.71 16.08h-5.42v13.89h5.42z");
}

.wus418bat {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.203 7.912l.002-.002l.002-.001l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.823");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x4d85ybrc {
  cx: 11.229px;
  cy: 10.631px;
  r: 1.669px;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yse58cb3o {
  d: path("M14.605 10.26c0-.289-.234-.48-.298-.539L14.02 10l.178.361z");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zfwdzhtah {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.614 13.388a2.96 2.96 0 0 0 1.362.323c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.986-.28l2.945.253m-2.945-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.207.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.868c-.681 0-1.28-.347-1.624-.868m3.207-.027a1.9 1.9 0 0 1-1.583.845a1.9 1.9 0 0 1-1.583-.845m-.041.027v.001l.041-.028m-.041.027l.041-.027");
}

.zg3sctqig {
  d: path("m15.594 10.346l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zpwemrbdg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.637 7.767c.43-.075 1.268-.054 1.849.398");
}

.zr8leoe3h {
  stop-color: var(--svg-color--cdbed0, #CDBED0);
}

</style>
