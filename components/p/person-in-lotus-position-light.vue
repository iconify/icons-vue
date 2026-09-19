<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRDOnIb)" clip-rule="evenodd" class="a03e9pb6i"/><path fill="url(#iCZ2Hpu)" clip-rule="evenodd" class="sq6qddbed"/><g filter="url(#ij9UvVc)"><path fill="url(#i5yfUMc)" class="r6t5fdb5z"/><path fill="url(#iSgtjHd)" class="r6t5fdb5z"/></g><path fill="url(#iA96PzE)" class="pr4ditbsi"/><path fill="url(#iKu4zId)" class="pr4ditbsi"/><g filter="url(#iLA5b9A)"><path class="dlop932ty"/></g><path fill="url(#i7HROGc)" class="qldr0kbme"/><path fill="url(#itiSbzd)" class="qldr0kbme"/><path fill="url(#iyhaOFe)" class="qldr0kbme"/><path fill="url(#iP40qfe)" class="sn5e1_b6a"/><path fill="url(#i8M2ibb)" class="sn5e1_b6a"/><path fill="url(#iISRgKb)" class="sn5e1_b6a"/><path fill="url(#iMzXytv)" class="bvc6mfb7j"/><path fill="url(#ixtAAry)" class="bvc6mfb7j"/><path fill="url(#ihQGM2b)" class="bvc6mfb7j"/><path class="q5ek91bxz"/><path fill="url(#iIzS8Qb)" class="m3g9c93kt"/><path fill="url(#iPoJlVb)" class="m3g9c93kt"/><path fill="url(#ifBJ4Ug)" class="m3g9c93kt"/><g filter="url(#ikAipld)"><path class="adjv9ubcq"/><path fill="url(#ip9rHpc)" class="s2exfcbyx"/><path fill="url(#irngmHd)" class="s2exfcbyx"/><path fill="url(#i78r8Sc)" class="s2exfcbyx"/></g><g filter="url(#isb85rd)"><path fill="url(#ixclxhc)" class="hvkhdmfad"/></g><g filter="url(#iLHqu7Z)"><path fill="url(#i7VR6Ry)" class="t6ernuw5h"/><path fill="url(#i9Ozx6d)" class="t6ernuw5h"/></g><g filter="url(#ihQa2Yc)"><path fill="url(#iG87RAB)" class="srj3oq2hf"/><path fill="url(#iJuWDSc)" class="srj3oq2hf"/></g><path fill="url(#iwIk1RP)" class="srj3oq2hf"/><path clip-rule="evenodd" class="dob5rviuo"/><path fill="url(#iNCc64l)" clip-rule="evenodd" class="x3hc4tb4e"/><path clip-rule="evenodd" class="nb1t54bir"/><path fill="url(#iviKZSX)" clip-rule="evenodd" class="gbcyzr76l"/><path clip-rule="evenodd" class="jlleovb-o"/><path fill="url(#i9ky2ne)" clip-rule="evenodd" class="jk4gd0bdm"/><path clip-rule="evenodd" class="otw__cbjw"/><path fill="url(#iTtxXdb)" clip-rule="evenodd" class="cd_2jstni"/><path clip-rule="evenodd" class="gyhpocb3d"/><path fill="url(#i7rFGII)" clip-rule="evenodd" class="jz-6pkbmo"/><path clip-rule="evenodd" class="x40ln-bnj"/><path fill="url(#inQw6Oe)" clip-rule="evenodd" class="nayex6koj"/><path clip-rule="evenodd" class="cm7234atb"/><path fill="url(#iTWRHAb)" clip-rule="evenodd" class="t-vc93b3o"/><path fill="url(#i5mA3oe)" clip-rule="evenodd" class="a4i5n45nj"/><path fill="url(#iiU4zIz)" clip-rule="evenodd" class="a4i5n45nj"/><g filter="url(#iT3uY1d)"><path class="x09w1trwj"/></g><g filter="url(#ip47UUw)"><path stroke="url(#icnQwfe)" class="tbpujzqai"/></g><g filter="url(#irK6XGb)"><path class="eczhn6bte"/></g><g filter="url(#i1X39pR)"><path stroke="url(#iW3DxZb)" class="u_pil8u_l"/></g><g filter="url(#icvt1Zd)"><path class="mp5pacluc"/></g><g filter="url(#iHdfHEd)"><path stroke="url(#itlXw6d)" class="dlmr9bcyu"/></g><g filter="url(#ibJ7nuW)"><path class="uokd_kbwg"/></g><g filter="url(#i9zIUbd)"><path stroke="url(#iDcX5Qb)" class="b0ry09b4q"/></g><path fill="url(#iW9a5bb)" class="r2vsp-b5w"/><path fill="url(#i8pIxid)" class="yg3b04buq"/><g filter="url(#iP0HIMe)"><path fill="url(#iXkeiGe)" class="ep12_wq0s"/></g><path fill="url(#iNq9dqb)" class="ep12_wq0s"/><path fill="url(#iITCZfd)" class="ep12_wq0s"/><path fill="url(#i60n1Gc)" class="ep12_wq0s"/><path fill="url(#iFdnNOb)" class="ep12_wq0s"/><path fill="url(#iEfCvQb)" class="ep12_wq0s"/><path fill="url(#iRjeajb)" class="ep12_wq0s"/><path fill="url(#i88Eo1b)" class="ep12_wq0s"/><g filter="url(#iJEK0qb)"><path class="e6br2achg"/></g><g filter="url(#iG11PHe)"><path class="lyj3kdbzj"/><path fill="url(#iwm20le)" class="gjhswf8si"/><path fill="url(#ialH6UR)" class="gjhswf8si"/><path fill="url(#id0NoJd)" class="gjhswf8si"/><path fill="url(#iFwGzSc)" class="gjhswf8si"/><path fill="url(#iQq6GHc)" class="gjhswf8si"/></g><g filter="url(#iCKnjec)"><path stroke="url(#iAxwJbc)" class="amoihxbht"/></g><path fill="url(#ip9ZEBc)" class="hdt-c7b3d"/><g filter="url(#iO5CnDd)"><path fill="url(#iOdwpRc)" class="db4y7eb7y"/><path fill="url(#iUQocZd)" class="db4y7eb7y"/><path fill="url(#ihbwI6c)" class="db4y7eb7y"/><path fill="url(#iFRcvcc)" class="db4y7eb7y"/><path fill="url(#isTDfDe)" class="db4y7eb7y"/></g><g filter="url(#iM7E6nd)"><path class="dmux-t14u"/></g><g filter="url(#ip259pd)"><path class="v-xskhbpp"/></g><g filter="url(#iIvJxAd)"><path class="jxn7ay8_k"/><path fill="url(#iejE7Ob)" class="hvyq7dbvp"/><path fill="url(#iBAM1Xp)" class="hvyq7dbvp"/></g><g filter="url(#iiuyqcc)"><path class="j77t98bnk"/><path fill="url(#ibROTzd)" class="ihesk3kfv"/><path fill="url(#iyaeZYc)" class="ihesk3kfv"/><path fill="url(#iSOCJwe)" class="ihesk3kfv"/></g><path fill="url(#ib0GrlM)" class="sueteibga"/><path fill="url(#il3Wd1c)" class="sueteibga"/><path fill="url(#iomfwwd)" class="sueteibga"/><path fill="url(#iyuxEwd)" class="sueteibga"/><path fill="url(#ivp5hdc)" class="bngh5jgtc"/><path fill="url(#iMTLQAI)" class="bngh5jgtc"/><g filter="url(#i8ss2Rb)"><path fill="url(#iGvUynY)" class="anmxrhb9j"/></g><g filter="url(#ikR1T6b)"><path fill="url(#iQa0Ndc)" class="ed3lrgbmv"/></g><g filter="url(#irO2gfd)"><path class="tshe33bus"/></g><g filter="url(#iMnWFAD)"><path class="fah8slf9j"/></g><path class="g7tzrok9x"/><g filter="url(#iLeJVLc)"><path class="wpo7vfbqs"/></g><path class="ovwybtw7l"/><g filter="url(#if1dyHc)"><path class="umoqnbb7f"/></g><defs><radialGradient id="iRDOnIb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.343 13.073)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="lsnfobzbz"/><stop offset="1" class="gf6fosb8y"/></radialGradient><radialGradient id="iCZ2Hpu" cx="0" cy="0" r="1" gradientTransform="rotate(174.454 13.31 11.969)scale(.83202 .3356)" gradientUnits="userSpaceOnUse"><stop class="cxkykm1df"/><stop offset="1" class="pgvvb0b4v"/></radialGradient><radialGradient id="i5yfUMc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.158)" gradientUnits="userSpaceOnUse"><stop class="ihlvscyun"/><stop offset="1" class="jr2ezs63s"/></radialGradient><radialGradient id="iSgtjHd" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.844 31.605)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="w_0x8cbdi"/><stop offset="1" class="u_uylxu0j"/></radialGradient><radialGradient id="iA96PzE" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.502)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="kaew0_2pl"/><stop offset="1" class="a-cjnzu_f"/></radialGradient><radialGradient id="iKu4zId" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.142)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="z260igbpj"/><stop offset="1" class="qcf9xbgxm"/></radialGradient><radialGradient id="i7HROGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.835)" gradientUnits="userSpaceOnUse"><stop class="s_ql7obry"/><stop offset="1" class="zpmzd2b_c"/></radialGradient><radialGradient id="itiSbzd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.71)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="f7iqbccaz"/><stop offset="1" class="ygetoyo1j"/></radialGradient><radialGradient id="iyhaOFe" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.845)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="jvt0tewya"/><stop offset="1" class="lpv9r5l0o"/></radialGradient><radialGradient id="iP40qfe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.064)" gradientUnits="userSpaceOnUse"><stop class="w20zx1b6w"/><stop offset="1" class="njjkphbnd"/></radialGradient><radialGradient id="iMzXytv" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.79)" gradientUnits="userSpaceOnUse"><stop class="bcwu99b2k"/><stop offset="1" class="ikuj7j5dl"/></radialGradient><radialGradient id="iIzS8Qb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.158 23.465)" gradientUnits="userSpaceOnUse"><stop class="nh2d_e3ja"/><stop offset="1" class="s1mkhyyat"/></radialGradient><radialGradient id="ifBJ4Ug" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 19.97)" gradientUnits="userSpaceOnUse"><stop class="k_38rrb4p"/><stop offset="1" class="jq958cc5h"/></radialGradient><radialGradient id="irngmHd" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.232 7.517)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="rx794hb8i"/><stop offset="1" class="jh2mh4wye"/></radialGradient><radialGradient id="i78r8Sc" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.064)" gradientUnits="userSpaceOnUse"><stop class="j2u72qbdb"/><stop offset="1" class="r2rd1hnwy"/></radialGradient><radialGradient id="ixclxhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.064)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="i7VR6Ry" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.06 2.384)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="epy_aimha"/><stop offset="1" class="p6bgw4n9x"/></radialGradient><radialGradient id="i9Ozx6d" cx="0" cy="0" r="1" gradientTransform="rotate(118.757 4.549 9.672)scale(3.02046 3.40652)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="tx5q7hblx"/><stop offset="1" class="iu30sbc6i"/></radialGradient><radialGradient id="iG87RAB" cx="0" cy="0" r="1" gradientTransform="matrix(.5 8.04173 -7.73502 .48093 17.689 13.252)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ydcxvabaw"/><stop offset="1" class="hekp_gbnf"/></radialGradient><radialGradient id="iJuWDSc" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.582 10.737)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="ksocwfbza"/><stop offset="1" class="ecaf6kbqo"/></radialGradient><radialGradient id="iwIk1RP" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.783)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="bmu4g5dxl"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="iNCc64l" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.017)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iviKZSX" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.017)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="i9ky2ne" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iTtxXdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="i7rFGII" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.197)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="inQw6Oe" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.745 24.099)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iTWRHAb" cx="0" cy="0" r="1" gradientTransform="rotate(84.646 -10.42 15.45)scale(1.07328 3.59749)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iiU4zIz" cx="0" cy="0" r="1" gradientTransform="rotate(95.537 1.963 24.072)scale(.99219 3.43822)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iW9a5bb" cx="0" cy="0" r="1" gradientTransform="matrix(.47013 1.26798 -1.50626 .55847 19.017 8.399)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i8pIxid" cx="0" cy="0" r="1" gradientTransform="matrix(.927 .29135 -.89882 2.85988 12.23 8.707)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iXkeiGe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28235 0 0 -5.80644 17.796 7.808)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iITCZfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.17805 -6.7724 0 16.4 3.933)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="surf7ac4k"/><stop offset=".96" class="sgq62lblp"/></radialGradient><radialGradient id="i60n1Gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.721 .89224 0 17.57 6.984)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iFdnNOb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 10.813 -3.814)scale(.68705 .74768)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iEfCvQb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.961 4.5)scale(5.34488 13.6535)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iRjeajb" cx="0" cy="0" r="1" gradientTransform="matrix(1.94536 -2.05797 .75336 .71214 12.6 5.092)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="i88Eo1b" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.458 7.291)scale(2.11524 1.7463)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="ialH6UR" cx="0" cy="0" r="1" gradientTransform="matrix(0 .15326 -.48168 0 16.325 8.662)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iFwGzSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95506 .43789 -.70372 -1.53486 16.398 8.304)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="ip9ZEBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.45252 1.8206 0 16.032 10.03)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iUQocZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.19833 5.55933 0 12.75 5.992)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ihbwI6c" cx="0" cy="0" r="1" gradientTransform="matrix(.0716 -1.57752 2.79505 .12686 19.085 6.815)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iFRcvcc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.481 -.97406 .715 -1.08713 18.611 2.874)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="isTDfDe" cx="0" cy="0" r="1" gradientTransform="matrix(.56828 .92608 -2.14438 1.31587 15.464 1.874)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iejE7Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38199 0 0 -.51291 16.192 3.293)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iBAM1Xp" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 11.544 -8.567)scale(3.78386 4.19212)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ibROTzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.92023 0 0 .75078 18.176 3.78)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iyaeZYc" cx="0" cy="0" r="1" gradientTransform="rotate(-43.614 15.95 -19.258)scale(2.323 4.25282)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iSOCJwe" cx="0" cy="0" r="1" gradientTransform="matrix(2.03941 .23839 -.0998 .85387 17.13 4.76)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="il3Wd1c" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 4.691 16.103)scale(1.4627 1.39553)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iomfwwd" cx="0" cy="0" r="1" gradientTransform="matrix(.49461 -.67878 .56895 .41458 19.157 7.583)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iyuxEwd" cx="0" cy="0" r="1" gradientTransform="matrix(.36855 -.97345 1.30065 .49243 19.23 7.691)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iMTLQAI" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 6.706 3.429)scale(1.02037 1.09532)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iGvUynY" cx="0" cy="0" r="1" gradientTransform="rotate(170.262 6.148 4.374)scale(.58383 .7164)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="ij9UvVc" width="9.729" height="6.156" x="17.627" y="21.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.521569 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23997" result="effect2_innerShadow_3987_23997"/></filter><filter id="iLA5b9A" width="17.213" height="8.245" x="5.751" y="21.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.658824 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.537255 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23997" result="effect2_innerShadow_3987_23997"/></filter><filter id="ikAipld" width="7.621" height="12.797" x="19.836" y="11.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/></filter><filter id="isb85rd" width="8.502" height="3.19" x="11.869" y="21.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/></filter><filter id="iLHqu7Z" width="5.834" height="4.108" x="13.158" y="10.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/></filter><filter id="ihQa2Yc" width="8.289" height="10.271" x="11.888" y="11.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.423529 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/></filter><filter id="iT3uY1d" width="1.684" height="1.255" x="5.351" y="23.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="ip47UUw" width="1.684" height="1.255" x="24.965" y="23.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="irK6XGb" width="2.04" height="1.095" x="4.237" y="23.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="i1X39pR" width="2.04" height="1.095" x="25.723" y="23.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="icvt1Zd" width="2.223" height=".888" x="3.593" y="23.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="iHdfHEd" width="2.223" height=".888" x="26.184" y="23.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="ibJ7nuW" width="2.031" height=".566" x="3.653" y="22.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="i9zIUbd" width="2.031" height=".566" x="26.317" y="22.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="iP0HIMe" width="7.417" height="7.949" x="12.854" y="3.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23997" result="effect2_innerShadow_3987_23997"/></filter><filter id="iJEK0qb" width="3.097" height="3.821" x="14.395" y="6.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".5"/></filter><filter id="iG11PHe" width="1.379" height="2.021" x="15.343" y="7.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><filter id="iCKnjec" width="2.521" height="1.174" x="14.772" y="9.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><filter id="iO5CnDd" width="8.082" height="5.433" x="11.992" y="1.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23997" result="effect2_innerShadow_3987_23997"/></filter><filter id="iM7E6nd" width="1.506" height=".822" x="17.03" y="5.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/></filter><filter id="ip259pd" width="1.506" height=".813" x="13.73" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/></filter><filter id="iIvJxAd" width="4.32" height="3.743" x="12.272" y="2.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23997"/><feGaussianBlur result="effect2_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><filter id="iiuyqcc" width="3.878" height="3.534" x="16.042" y="2.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".075"/></filter><filter id="i8ss2Rb" width="1.02" height="1.68" x="12.122" y="6.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".125"/></filter><filter id="ikR1T6b" width="1.594" height="2.195" x="18.675" y="6.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".25"/></filter><filter id="irO2gfd" width="1.339" height=".558" x="13.765" y="5.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><filter id="iMnWFAD" width="1.339" height=".558" x="17.079" y="5.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><filter id="iLeJVLc" width="1.628" height=".644" x="13.82" y="7.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><filter id="if1dyHc" width="1.628" height=".644" x="16.609" y="7.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23997" stdDeviation=".05"/></filter><linearGradient id="i8M2ibb" x1="21.525" x2="21.525" y1="21.002" y2="22.158" gradientUnits="userSpaceOnUse"><stop class="h58pkjbsd"/><stop offset="1" class="pub21ekls"/></linearGradient><linearGradient id="iISRgKb" x1="18.658" x2="19.892" y1="24.286" y2="24.689" gradientUnits="userSpaceOnUse"><stop offset=".106" class="l2-xyub4i"/><stop offset="1" class="yi9dofbqv"/></linearGradient><linearGradient id="ixtAAry" x1="10.822" x2="10.822" y1="21.002" y2="22.158" gradientUnits="userSpaceOnUse"><stop class="w9r_6_bym"/><stop offset="1" class="v6lc275im"/></linearGradient><linearGradient id="ihQGM2b" x1="13.689" x2="12.455" y1="24.286" y2="24.689" gradientUnits="userSpaceOnUse"><stop offset=".106" class="d934ondjd"/><stop offset="1" class="vcwi5gbcl"/></linearGradient><linearGradient id="iPoJlVb" x1="12.24" x2="10.033" y1="20.607" y2="20.417" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sl8i30onx"/><stop offset="1" class="b39l_ob7e"/></linearGradient><linearGradient id="ip9rHpc" x1="19.835" x2="22.042" y1="20.607" y2="20.417" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bvjkc1dux"/><stop offset="1" class="im_-qcomr"/></linearGradient><linearGradient id="i5mA3oe" x1="26.505" x2="25.169" y1="25.217" y2="24.061" gradientUnits="userSpaceOnUse"><stop offset=".569" class="s_h949kal"/><stop offset="1" class="f-865jbco"/></linearGradient><linearGradient id="icnQwfe" x1="26.516" x2="25.268" y1="25.084" y2="24.957" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iW3DxZb" x1="27.656" x2="26.075" y1="24.764" y2="24.504" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="itlXw6d" x1="28.314" x2="26.645" y1="24.018" y2="24.114" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iDcX5Qb" x1="28.24" x2="26.724" y1="23.243" y2="23.181" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iNq9dqb" x1="19.271" x2="16.538" y1="8.866" y2="8.866" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iwm20le" x1="16.558" x2="16.032" y1="8.231" y2="8.253" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="id0NoJd" x1="16.032" x2="16.032" y1="8.947" y2="8.655" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iQq6GHc" x1="16.032" x2="16.032" y1="7.167" y2="7.592" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iAxwJbc" x1="15.278" x2="15.478" y1="9.933" y2="9.409" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="iOdwpRc" x1="20.335" x2="13.044" y1="4.253" y2="4.253" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ib0GrlM" x1="20.073" x2="19.316" y1="7.283" y2="8.65" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="ivp5hdc" x1="12.36" x2="13.276" y1="7.725" y2="7.645" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iQa0Ndc" x1="19.472" x2="19.472" y1="7.05" y2="8.245" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-lotus-position-light" /></template>
<style>
.a-cjnzu_f {
  stop-color: var(--svg-color--c38390, #C38390);
}

.a03e9pb6i {
  fill-rule: evenodd;
  d: path("M6.76 22.928a.5.5 0 0 1-.5.5c-.632 0-1.257-.194-1.501-.269l-.04-.012a.5.5 0 1 1 .293-.956l.029.009c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a4i5n45nj {
  fill-rule: evenodd;
  d: path("M25.276 24.143c-.14.17-.273.304-.102.444c.566.463.85.628 1.109.76l.072.036a.4.4 0 0 0 .367-.71l-.075-.039c-.242-.123-.38-.122-.879-.532c-.17-.14-.352-.13-.492.041");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.adjv9ubcq {
  fill: var(--svg-color--f0b99e, #F0B99E);
  d: path("M22.32 16.051c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315V19.6c.25.651.719 1.329 1.125 1.652c0 0 .867.814 4.172 3.303c1.325-.184 2.094-1.093 2.073-1.703c-.874-.5-3.37-2.968-4.01-3.606c-.538-.535-.641-1.215-.876-3.196");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.amoihxbht {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.197 9.354c.24.125.528.197.835.197c.31 0 .595-.072.835-.197h.001a.17.17 0 0 1 .203.033c.048.05.067.133.018.206m-1.892-.24l1.83.198m-1.83-.197a.17.17 0 0 0-.204.034a.16.16 0 0 0-.017.205m.221-.24l-.159.198m2.05.042l-.062-.042m.063.042l-.063-.042m.063.042a1.26 1.26 0 0 1-1.057.565c-.443 0-.832-.226-1.056-.565m2.05-.042c-.21.32-.576.532-.994.532c-.417 0-.784-.213-.994-.532m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.anmxrhb9j {
  d: path("M12.84 7.055a.6.6 0 0 0 .052 1.18q-.034-.59-.052-1.18");
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b0ry09b4q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.236c-.398 0-.893.047-1.58-.11");
}

.b39l_ob7e {
  stop-color: var(--svg-color--df947d, #DF947D);
  stop-opacity: 0;
}

.bcwu99b2k {
  stop-color: var(--svg-color--f2b59c, #F2B59C);
}

.bmu4g5dxl {
  stop-color: var(--svg-color--c56d32, #C56D32);
}

.bngh5jgtc {
  d: path("M12.866 6.64a1.01 1.01 0 0 0 .08 2.01a50 50 0 0 1-.08-2.01");
}

.bvc6mfb7j {
  d: path("M13.83 21.294H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bvjkc1dux {
  stop-color: var(--svg-color--dc8368, #DC8368);
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cd_2jstni {
  fill-rule: evenodd;
  d: path("M26.175 23.496a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 1 0 0-.8a3.6 3.6 0 0 1-1.466-.365a.4.4 0 0 0-.537.18");
}

.cm7234atb {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M6.818 24.142c.14.171.272.304.101.444a6 6 0 0 1-1.265.82a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.175");
}

.cxkykm1df {
  stop-color: var(--svg-color--efc3ad, #EFC3AD);
}

.d934ondjd {
  stop-color: var(--svg-color--b17369, #B17369);
}

.db4y7eb7y {
  d: path("M19.081 3.637a1.487 1.487 0 0 1 .729 2.246a1 1 0 0 0-.17.55v.745a1.1 1.1 0 0 0-.419-.168L19.272 6a.91.91 0 0 0-.866-.899h-.88a1.52 1.52 0 0 1-1.388-.906a.42.42 0 0 0-.386-.263h-.8a2.11 2.11 0 0 0-2.097 2.122l.02.965a1.1 1.1 0 0 0-.453.166v-.754a1 1 0 0 0-.17-.549a1.5 1.5 0 0 1-.09-1.535c.183-.347.48-.59.816-.708c.36-.128.666-.37.87-.697a1.46 1.46 0 0 1 1.814-.572a.94.94 0 0 0 .75 0c.176-.074.369-.118.572-.118c.53 0 .992.286 1.249.71c.193.32.496.553.849.674");
}

.dlmr9bcyu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 23.986a3.8 3.8 0 0 1-1.773-.437");
}

.dlop932ty {
  fill: var(--svg-color--fdcab1, #FDCAB1);
  d: path("M10.236 27.908c-2.93 0-4.281-1.917-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086c.426 0 .804.268.944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.dmux-t14u {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.376 5.937a1.2 1.2 0 0 0-.432-.258c-.191-.06-.43-.077-.761-.036a.174.174 0 1 0 .042.346c.302-.037.487-.018.614.022c.125.039.21.103.308.189a.174.174 0 1 0 .229-.263");
}

.dob5rviuo {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M5.697 23.017a.4.4 0 0 1-.266.5c-.536.164-1.099.146-1.367.137q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.002c.286.008.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e0us9sblp {
  stop-color: var(--svg-color--eec0af, #EEC0AF);
}

.e6br2achg {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.78 7.479l-.37 1.154c-.064.237.088.475.304.475h.46c.215 0 .367-.241.303-.475l-.31-1.154c-.067-.256-.317-.256-.387 0");
}

.ecaf6kbqo {
  stop-color: var(--svg-color--cc3a05, #CC3A05);
}

.eczhn6bte {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.717c.41-.067 1.204-.313 1.59-.645");
}

.ed3lrgbmv {
  d: path("M19.175 8.245q.037-.597.07-1.195a.6.6 0 0 1-.07 1.195");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ep12_wq0s {
  d: path("M13.004 9.544a2.46 2.46 0 0 0 2.44 2.138h1.184a2.46 2.46 0 0 0 2.44-2.138c.073-1.183.148-2.36.203-3.543a.91.91 0 0 0-.866-.899h-.879a1.52 1.52 0 0 1-1.389-.906a.42.42 0 0 0-.386-.263h-.8a2.11 2.11 0 0 0-2.097 2.122c0 1.168.073 2.318.15 3.489");
}

.epy_aimha {
  stop-color: var(--svg-color--ffceb8, #FFCEB8);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-865jbco {
  stop-color: var(--svg-color--da9982, #DA9982);
}

.f7iqbccaz {
  stop-color: var(--svg-color--ffcab4, #FFCAB4);
}

.fah8slf9j {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.268 6.015a1.45 1.45 0 0 0-1.04-.24");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
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

.ft5dv1b6b {
  fill: none;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.g7tzrok9x {
  stroke: var(--svg-color--4b3833, #4B3833);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.274a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.gbcyzr76l {
  fill-rule: evenodd;
  d: path("M26.304 23.017a.4.4 0 0 0 .265.5c.536.164 1.099.146 1.367.137q.082-.003.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.002c-.286.008-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.gf6fosb8y {
  stop-color: var(--svg-color--ffc2a4, #FFC2A4);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gjhswf8si {
  d: path("m15.792 7.36l-.333 1.153c-.069.238.095.475.326.475h.494c.232 0 .395-.24.327-.475l-.334-1.154c-.071-.256-.405-.256-.48 0");
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gyhpocb3d {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M6.099 23.918a.4.4 0 0 1-.044.563c-.34.29-.628.457-.903.55a2.5 2.5 0 0 1-.655.113l-.037.003a.4.4 0 0 1-.057-.798l.018-.002c.19-.013.32-.022.475-.074c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.044");
}

.h58pkjbsd {
  stop-color: var(--svg-color--b66c55, #B66C55);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hdt-c7b3d {
  d: path("M16.032 9.626c-.318 0-.618-.075-.87-.206c-.086-.044-.178.053-.124.131c.21.32.577.532.994.532s.784-.213.994-.532c.055-.08-.038-.175-.124-.13a1.9 1.9 0 0 1-.87.205");
}

.hekp_gbnf {
  stop-color: var(--svg-color--f74d05, #F74D05);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hvkhdmfad {
  d: path("m13.447 24.283l-1.578-2.99h8.301l-1.551 2.99z");
}

.hvyq7dbvp {
  d: path("m16.179 4.282l-.042-.086a.42.42 0 0 0-.386-.263h-.8a2.11 2.11 0 0 0-2.097 2.122v.173c-.214-.163-.482-.505-.482-1.06c0-.673.49-1.013.803-1.23a1.4 1.4 0 0 0 .208-.16q.03-.028.063-.065c.22-.233.61-.647 1.293-.829c.22-.058.44-.087.645-.099c.472-.026.808.385.808.858v.63z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihesk3kfv {
  d: path("m19.306 6.333l-.019-.396a.92.92 0 0 0-.882-.895h-.88a1.52 1.52 0 0 1-1.333-.791s.453-1.306 1.203-1.137c.548.124 1.135.318 1.584.61c1.095.715.903 2.003.326 2.609");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ihlvscyun {
  stop-color: var(--svg-color--e2b3a5, #E2B3A5);
}

.ikuj7j5dl {
  stop-color: var(--svg-color--ce927d, #CE927D);
}

.im_-qcomr {
  stop-color: var(--svg-color--dc8368, #DC8368);
  stop-opacity: 0;
}

.iu30sbc6i {
  stop-color: var(--svg-color--e6ab90, #E6AB90);
  stop-opacity: 0;
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.j77t98bnk {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.306 6.333l-.019-.396a.92.92 0 0 0-.882-.895h-.88a1.52 1.52 0 0 1-1.333-.791s.453-1.306 1.203-1.137c.548.124 1.135.318 1.584.61c1.095.715.903 2.003.326 2.609");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jh2mh4wye {
  stop-color: var(--svg-color--f1c0a6, #F1C0A6);
  stop-opacity: 0;
}

.jk4gd0bdm {
  fill-rule: evenodd;
  d: path("M5.825 23.496a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 1 1 0-.8c.226 0 .852-.06 1.466-.365a.4.4 0 0 1 .537.18");
}

.jlleovb-o {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M5.825 23.496a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 1 1 0-.8c.226 0 .852-.06 1.466-.365a.4.4 0 0 1 .537.18");
}

.jq958cc5h {
  stop-color: var(--svg-color--d2826a, #D2826A);
  stop-opacity: 0;
}

.jr2ezs63s {
  stop-color: var(--svg-color--f1b9a0, #F1B9A0);
}

.jvt0tewya {
  stop-color: var(--svg-color--f3a98c, #F3A98C);
}

.jxn7ay8_k {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.179 4.282l-.042-.086a.42.42 0 0 0-.386-.263h-.8a2.11 2.11 0 0 0-2.097 2.122v.173c-.214-.163-.482-.505-.482-1.06c0-.673.49-1.013.803-1.23a1.4 1.4 0 0 0 .208-.16q.03-.028.063-.065c.22-.233.61-.647 1.293-.829c.22-.058.44-.087.645-.099c.472-.026.808.385.808.858v.63z");
}

.jz-6pkbmo {
  fill-rule: evenodd;
  d: path("M6.099 23.918a.4.4 0 0 1-.044.563c-.34.29-.628.457-.903.55a2.5 2.5 0 0 1-.655.113l-.037.003a.4.4 0 0 1-.057-.798l.018-.002c.19-.013.32-.022.475-.074c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.044");
}

.k_38rrb4p {
  stop-color: var(--svg-color--ac5d47, #AC5D47);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kaew0_2pl {
  stop-color: var(--svg-color--dc9fa1, #DC9FA1);
}

.ksocwfbza {
  stop-color: var(--svg-color--ee5422, #EE5422);
  stop-opacity: 0;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2-xyub4i {
  stop-color: var(--svg-color--af7875, #AF7875);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lpv9r5l0o {
  stop-color: var(--svg-color--f3a98c, #F3A98C);
  stop-opacity: 0;
}

.lsnfobzbz {
  stop-color: var(--svg-color--fdc3a2, #FDC3A2);
}

.lyj3kdbzj {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.792 7.36l-.333 1.153c-.069.238.095.475.326.475h.494c.232 0 .395-.24.327-.475l-.334-1.154c-.071-.256-.405-.256-.48 0");
}

.m3g9c93kt {
  d: path("M9.755 16.051c.22-1.858 1.605-3.58 2.152-4.041l.332.315V19.6c-.25.651-.719 1.329-1.125 1.652c0 0-.867.814-4.171 3.303c-1.325-.184-2.095-1.093-2.074-1.703c.875-.5 3.37-2.968 4.011-3.606c.537-.535.64-1.215.875-3.196");
}

.m69lyob2q {
  stop-color: var(--svg-color--d69f8f, #D69F8F);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mp5pacluc {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 23.986c.398 0 1.015-.055 1.773-.437");
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n6m3gkbee {
  stop-color: var(--svg-color--e0a6a7, #E0A6A7);
  stop-opacity: 0;
}

.nayex6koj {
  fill-rule: evenodd;
  d: path("M25.902 23.918a.4.4 0 0 0 .043.563c.34.29.628.457.903.55c.254.085.478.1.655.113l.037.003a.4.4 0 0 0 .057-.798l-.018-.002a1.8 1.8 0 0 1-.474-.074c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.044");
}

.nb1t54bir {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M26.304 23.017a.4.4 0 0 0 .265.5c.536.164 1.099.146 1.367.137q.082-.003.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.002c-.286.008-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.nh2d_e3ja {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
}

.njjkphbnd {
  stop-color: var(--svg-color--ce8c76, #CE8C76);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.otw__cbjw {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M26.175 23.496a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 1 0 0-.8a3.6 3.6 0 0 1-1.466-.365a.4.4 0 0 0-.537.18");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ovwybtw7l {
  stroke: var(--svg-color--4b3833, #4B3833);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.274a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.p6bgw4n9x {
  stop-color: var(--svg-color--f5bca5, #F5BCA5);
}

.pgvvb0b4v {
  stop-color: var(--svg-color--eabfa6, #EABFA6);
}

.pr4ditbsi {
  d: path("M13.22 24.283h-1.429a1 1 0 0 0-.943.67c-.408 1.17-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.872 2.057-1.735l.052-.078h.42z");
}

.pub21ekls {
  stop-color: var(--svg-color--cd846b, #CD846B);
  stop-opacity: 0;
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q5ek91bxz {
  fill: var(--svg-color--fabc9f, #FABC9F);
  d: path("M9.755 16.051c.22-1.858 1.605-3.58 2.152-4.041l.332.315V19.6c-.25.651-.719 1.329-1.125 1.652c0 0-.867.814-4.171 3.303c-1.325-.184-2.095-1.093-2.074-1.703c.875-.5 3.37-2.968 4.011-3.606c.537-.535.64-1.215.875-3.196");
}

.qcf9xbgxm {
  stop-color: var(--svg-color--f9bcae, #F9BCAE);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qldr0kbme {
  d: path("M10.236 27.908c-2.93 0-4.281-1.917-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086c.426 0 .804.268.944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.r2rd1hnwy {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
  stop-opacity: 0;
}

.r2vsp-b5w {
  d: path("M19.085 8.593a1.03 1.03 0 0 0 .568-.194v.584c0 .561-.334 1.06-.842 1.268q.161-.343.217-.74z");
}

.r6t5fdb5z {
  d: path("M17.627 27.908h4.244c2.93 0 4.28-1.917 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.109z");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rx794hb8i {
  stop-color: var(--svg-color--f0c1ae, #F0C1AE);
}

.s_h949kal {
  stop-color: var(--svg-color--e4b6a0, #E4B6A0);
}

.s_ql7obry {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
}

.s1mkhyyat {
  stop-color: var(--svg-color--efba94, #EFBA94);
  stop-opacity: 0;
}

.s2exfcbyx {
  d: path("M22.32 16.051c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315V19.6c.25.651.719 1.329 1.125 1.652c0 0 .867.814 4.172 3.303c1.325-.184 2.094-1.093 2.073-1.703c-.874-.5-3.37-2.968-4.01-3.606c-.538-.535-.641-1.215-.876-3.196");
}

.s86ss6vyf {
  stop-color: var(--svg-color--d69f8f, #D69F8F);
  stop-opacity: 0;
}

.sgq62lblp {
  stop-color: var(--svg-color--db9789, #DB9789);
}

.sl8i30onx {
  stop-color: var(--svg-color--df947d, #DF947D);
}

.sn5e1_b6a {
  d: path("M18.517 21.294h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sq6qddbed {
  fill-rule: evenodd;
  d: path("M25.316 22.928a.5.5 0 0 0 .5.5c.632 0 1.257-.194 1.5-.269l.04-.012a.5.5 0 1 0-.292-.956l-.03.009c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.srj3oq2hf {
  d: path("M18.892 11.124v.721a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.723a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.56-1.285-.895");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sueteibga {
  d: path("M19.123 8.65q.061-1.002.115-2.004a1.01 1.01 0 0 1-.115 2.004");
}

.surf7ac4k {
  stop-color: var(--svg-color--eab1a5, #EAB1A5);
  stop-opacity: 0;
}

.t-vc93b3o {
  fill-rule: evenodd;
  d: path("M6.818 24.142c.14.171.272.304.101.444a6 6 0 0 1-1.265.82a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.175");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t6ernuw5h {
  d: path("M18.892 11.124v.721a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.723c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.374 2.82.786");
}

.tbpujzqai {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.025c-.25-.146-.847-.51-1.234-.804");
}

.tshe33bus {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.915 6.044c.16-.116.563-.32 1.039-.24");
}

.tx5q7hblx {
  stop-color: var(--svg-color--de9b7b, #DE9B7B);
}

.u_pil8u_l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.717c-.41-.067-1.204-.313-1.59-.645");
}

.u_uylxu0j {
  stop-color: var(--svg-color--d08c76, #D08C76);
  stop-opacity: 0;
}

.umoqnbb7f {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.274a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uokd_kbwg {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.236c.398 0 .893.047 1.58-.11");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v-xskhbpp {
  fill: var(--svg-color--202020, #202020);
  d: path("M13.89 5.869a1.74 1.74 0 0 1 1.092-.226a.174.174 0 0 1-.042.346a1.4 1.4 0 0 0-.917.209l-.01.007l-.003.001a.174.174 0 0 1-.213-.275z");
}

.v6lc275im {
  stop-color: var(--svg-color--c5856f, #C5856F);
  stop-opacity: 0;
}

.vcwi5gbcl {
  stop-color: var(--svg-color--c98e79, #C98E79);
  stop-opacity: 0;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.w_0x8cbdi {
  stop-color: var(--svg-color--d08c76, #D08C76);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w20zx1b6w {
  stop-color: var(--svg-color--ce9b8a, #CE9B8A);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w9r_6_bym {
  stop-color: var(--svg-color--b3715e, #B3715E);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wp12h1b1k {
  stop-color: var(--svg-color--eec0af, #EEC0AF);
  stop-opacity: 0;
}

.wpo7vfbqs {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.274a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x09w1trwj {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.025c.25-.146.847-.51 1.234-.804");
}

.x3hc4tb4e {
  fill-rule: evenodd;
  d: path("M5.697 23.017a.4.4 0 0 1-.266.5c-.536.164-1.099.146-1.367.137q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.002c.286.008.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.x40ln-bnj {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M25.902 23.918a.4.4 0 0 0 .043.563c.34.29.628.457.903.55c.254.085.478.1.655.113l.037.003a.4.4 0 0 0 .057-.798l-.018-.002a1.8 1.8 0 0 1-.474-.074c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.044");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ydcxvabaw {
  stop-color: var(--svg-color--ff7d3c, #FF7D3C);
}

.yg3b04buq {
  d: path("M12.98 8.593a1.03 1.03 0 0 1-.567-.194v.584c0 .561.334 1.06.841 1.268a2.6 2.6 0 0 1-.217-.74z");
}

.ygetoyo1j {
  stop-color: var(--svg-color--ffcab4, #FFCAB4);
  stop-opacity: 0;
}

.yi9dofbqv {
  stop-color: var(--svg-color--c79383, #C79383);
  stop-opacity: 0;
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z260igbpj {
  stop-color: var(--svg-color--f9bcae, #F9BCAE);
  stop-opacity: 0;
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zk-sr297c {
  stop-color: var(--svg-color--e0a6a7, #E0A6A7);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zpmzd2b_c {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
