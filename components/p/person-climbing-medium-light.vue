<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#inuGCPd)" class="gpobzabhu"/><path fill="url(#iaVyXte)" class="gpobzabhu"/><path fill="url(#ixUafQe)" class="vgqexrbdw"/><path fill="url(#iZTheSb)" class="vgqexrbdw"/><path fill="url(#i18unxC)" class="vgqexrbdw"/><path fill="url(#iHBWKPb)" class="vgqexrbdw"/><path fill="url(#iYPfmVd)" class="vgqexrbdw"/><g filter="url(#iKDjXne)"><path class="hecffrsxz"/></g><path fill="url(#ikv1OYc)" class="vrat0nbqn"/><path fill="url(#ie43Y6b)" class="vrat0nbqn"/><path fill="url(#iq2rObJ)" class="vrat0nbqn"/><g filter="url(#ikG50KR)"><path fill="url(#iaZcX1c)" class="y46mnhndx"/></g><g filter="url(#iTBVMEc)"><path fill="url(#iCtdGFb)" clip-rule="evenodd" class="ks1_esbqd"/></g><g filter="url(#idk10rt)"><path stroke="url(#iahcyOc)" class="pa0ye030w"/></g><path fill="url(#iRnvlXc)" class="vrwnjxbrf"/><path fill="url(#i1Yst4w)" class="vrwnjxbrf"/><path fill="url(#iJEsPib)" class="vrwnjxbrf"/><g filter="url(#ij74i1d)"><path fill="url(#iTqyvFu)" class="yoiyyhbuh"/></g><g filter="url(#i5KNQvc)"><path fill="url(#i61UAve)" class="z-4xjv8km"/></g><path fill="url(#iqLsH7b)" class="zach8zb-s"/><path fill="url(#iToqO5A)" class="qnag9id6v"/><path fill="url(#ibX9psc)" class="qnag9id6v"/><path fill="url(#iHe62fe)" class="qnag9id6v"/><path fill="url(#ipEmNPe)" transform="rotate(7.73 23.43 10.897)" class="ubnjkbb9g"/><g filter="url(#iIx3z8c)"><path fill="url(#iPFT5tc)" class="wxwfcehps"/><path fill="url(#inKl4oe)" class="wxwfcehps"/></g><path fill="url(#izzeJXI)" clip-rule="evenodd" class="dlvk5ybil"/><path fill="url(#iJFHmWb)" clip-rule="evenodd" class="f1q29qbun"/><path fill="url(#iZXcJsd)" clip-rule="evenodd" class="f1q29qbun"/><path clip-rule="evenodd" class="m_hdbfh7v"/><g filter="url(#i1ki0qb)"><path class="ilfznfb_s"/><path fill="url(#iDURQLc)" class="rh20j3bdy"/></g><path class="jonyfxbku"/><g filter="url(#iboNeJb)"><path class="kjz5zrf_f"/><path fill="url(#iTqYocd)" class="l6j0rsiac"/><path fill="url(#ir2EThq)" class="l6j0rsiac"/></g><path class="revn8gesq"/><path fill="url(#idchNtx)" class="kr3h2mtpz"/><path fill="url(#iLKM4lb)" class="kr3h2mtpz"/><path fill="url(#ipaJeOc)" class="kr3h2mtpz"/><path fill="url(#iXdJxpc)" class="kr3h2mtpz"/><path fill="url(#iiNKhod)" class="bd7clsboy"/><path class="qqun0kp3y"/><circle class="gtns2tbea"/><path fill="url(#iSDxsPb)" class="diqc8voui"/><path fill="url(#i7woDIC)" class="diqc8voui"/><path fill="url(#iHe7J2y)" class="diqc8voui"/><path fill="url(#iVhL3AJ)" class="diqc8voui"/><path fill="url(#i6rq9Eb)" class="diqc8voui"/><g filter="url(#iQU8OCc)"><path class="q-jcn22bi"/><path fill="url(#i54lzzc)" class="iecr_084e"/><path fill="url(#iv0qYUd)" class="iecr_084e"/><path fill="url(#iGmmE2c)" class="iecr_084e"/></g><g filter="url(#iCIBhie)"><path class="xyrev7w3n"/><path fill="url(#i7iqcFd)" class="apb0ltxnb"/></g><g filter="url(#iC3tBBe)"><path class="gppwtlz2l"/><path fill="url(#iiKCfuS)" class="qle60tltw"/><path fill="url(#iNqt4Yb)" class="qle60tltw"/><path fill="url(#iNmQX9I)" class="qle60tltw"/></g><g filter="url(#i069C1h)"><path class="nku6vgp_t"/><path fill="url(#iiKCfuS)" class="qle60tltw"/><path fill="url(#iNqt4Yb)" class="qle60tltw"/><path fill="url(#iNmQX9I)" class="qle60tltw"/></g><g filter="url(#iq96zFc)"><path class="z1kr6xzoo"/><path fill="url(#i3ckZ4c)" class="mqbi9fb1c"/></g><path fill="url(#iOFXx8c)" clip-rule="evenodd" class="i5u7mbb_e"/><path fill="url(#i7WfFTc)" clip-rule="evenodd" class="i5u7mbb_e"/><path fill="url(#iSktCWn)" clip-rule="evenodd" class="i5u7mbb_e"/><path class="w_i4jlbaj"/><path fill="url(#izs5JRc)" class="euzvt6bws"/><path fill="url(#iBOrnZc)" class="euzvt6bws"/><path class="j14n23bil"/><path fill="url(#io6aCdd)" class="g8vkilb5t"/><path class="v5ir-udep"/><path fill="url(#i7oc0qb)" class="ub86ttbns"/><path class="tjcgz75aq"/><path fill="url(#iJIwGpe)" class="exhdqvblc"/><circle fill="url(#iRvaO4b)" class="z_c6qsb5g"/><path clip-rule="evenodd" class="l9mu7xbce"/><path fill="url(#iWzE1pb)" clip-rule="evenodd" class="uxye37bbx"/><path fill="url(#iRlqTmc)" clip-rule="evenodd" class="uxye37bbx"/><path fill="url(#igX6vDe)" clip-rule="evenodd" class="uxye37bbx"/><g filter="url(#iHLhIED)"><path fill="url(#iEBsuFd)" class="wbuujvb8l"/></g><g filter="url(#ilDjvyA)"><path fill="url(#iVpQxzb)" class="lxwwy-b-c"/></g><path class="bxjhn945r"/><path fill="url(#iPJSHZb)" class="mddv4hbgz"/><g filter="url(#ikBi1Jc)"><path clip-rule="evenodd" class="r3ssxeblm"/></g><path fill="url(#ignb8tb)" class="pjyyhbb1f"/><path fill="url(#iM8JJsc)" class="pjyyhbb1f"/><path fill="url(#ifBW7Tb)" class="pjyyhbb1f"/><path fill="url(#i8JKS5S)" class="qqtnb1ism"/><path fill="url(#i4jo5ce)" class="qqtnb1ism"/><path fill="url(#i849U2c)" class="qqtnb1ism"/><path class="c88tyqz5u"/><path class="uph363bnf"/><g filter="url(#iGcMI9g)"><path class="cflw04u6i"/></g><defs><radialGradient id="inuGCPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.204 28.594)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="i18unxC" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.097 5.4)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iHBWKPb" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 2.992 10.65)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iYPfmVd" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.611 21.47)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="iq2rObJ" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.338 5.302)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="iCtdGFb" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.475 18.853)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="f_1v57bhd"/><stop offset="1" class="pl76o5b_i"/></radialGradient><radialGradient id="i1Yst4w" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.054 8.632)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="iTqyvFu" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 12.861 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="iqLsH7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.68 8.146)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="p62i0qb1k"/><stop offset="1" class="d7aonq0wf"/></radialGradient><radialGradient id="ibX9psc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.252 21.672)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iHe62fe" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.174 19.192)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="ipEmNPe" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.738 11.966)" gradientUnits="userSpaceOnUse"><stop class="nk-mbmbtk"/><stop offset="1" class="db1j3cbeu"/></radialGradient><radialGradient id="iPFT5tc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 22.86 8.767)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gro4u4t-y"/><stop offset="1" class="x8-nb-ihc"/></radialGradient><radialGradient id="inKl4oe" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.165 11.938)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="wxl7pfshq"/><stop offset="1" class="ghwh3eklg"/></radialGradient><radialGradient id="iZXcJsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.709 19.563)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iDURQLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7533 -.625 .19855 -.2393 25.82 10.854)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="kg1ehzbwj"/><stop offset="1" class="e7o2u97gd"/></radialGradient><radialGradient id="ir2EThq" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.344 22.042)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="bylttzbhe"/><stop offset="1" class="f7ds2glhm"/></radialGradient><radialGradient id="idchNtx" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.082 9.991)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iLKM4lb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.695 13.294)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iXdJxpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.799 28.282)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="i7woDIC" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 9.985 11.717)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="qksuzsbug"/><stop offset="1" class="se__e0blq"/></radialGradient><radialGradient id="iHe7J2y" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.549 11.766)" gradientUnits="userSpaceOnUse"><stop class="jfz0xgwum"/><stop offset="1" class="k2u_13bdd"/></radialGradient><radialGradient id="iVhL3AJ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.627 14.141)" gradientUnits="userSpaceOnUse"><stop class="n_geicc-w"/><stop offset="1" class="bn_1vkbwm"/></radialGradient><radialGradient id="i6rq9Eb" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.205 15.297)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="nvv1klhll"/><stop offset="1" class="ilft87v6y"/></radialGradient><radialGradient id="i54lzzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.393 21.813)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iv0qYUd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 19.94 19.688)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="iGmmE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.814 19.61)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="iiKCfuS" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.299 17.875)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="iNmQX9I" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.002 17.22)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="i3ckZ4c" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.236 19.375)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="iSktCWn" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.658 16.172)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="izs5JRc" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.68 6.776)" gradientUnits="userSpaceOnUse"><stop class="r_5s-tw4v"/><stop offset="1" class="kqp9fdbzy"/></radialGradient><radialGradient id="iBOrnZc" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.414 7.568)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="czdn7vy6a"/><stop offset="1" class="gk9uazn2k"/></radialGradient><radialGradient id="iRvaO4b" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.365 18.704)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="a0px9dj6c"/><stop offset="1" class="ufi1sccsl"/></radialGradient><radialGradient id="igX6vDe" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.65 9.672)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iEBsuFd" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.542 9.902)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iVpQxzb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.361 8.375)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="ignb8tb" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.392 6.92)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="iM8JJsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.44 19.625)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="ifBW7Tb" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.161 19.726)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="i8JKS5S" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.236 16.104)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="o6w7f1w7w"/><stop offset="1" class="v5m-xebtg"/></radialGradient><radialGradient id="i849U2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.393 13.094)" gradientUnits="userSpaceOnUse"><stop class="xapik5b0z"/><stop offset="1" class="npx64-mvq"/></radialGradient><linearGradient id="iaVyXte" x1="11.136" x2="11.136" y1="30.141" y2="28.846" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="ixUafQe" x1="5.018" x2="6.174" y1="17.719" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="iZTheSb" x1="5.518" x2="5.861" y1="17.719" y2="18.688" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="ikv1OYc" x1="13.111" x2="11.268" y1="2.032" y2="15.157" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="ie43Y6b" x1="2.299" x2="12.83" y1="17.907" y2="13.751" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iaZcX1c" x1="13.967" x2="16.568" y1="10.858" y2="15.376" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="iahcyOc" x1="19.141" x2="21.359" y1="7.865" y2="11.802" gradientUnits="userSpaceOnUse"><stop class="v8ombmbjb"/><stop offset="1" class="r1g9oggar"/></linearGradient><linearGradient id="iRnvlXc" x1="4.205" x2="6.58" y1="5.438" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iJEsPib" x1="5.486" x2="5.205" y1="14.329" y2="13.329" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="i61UAve" x1="19.274" x2="20.633" y1="11.14" y2="15.8" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iToqO5A" x1="24.799" x2="26.205" y1="20.485" y2="20.485" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="izzeJXI" x1="24.573" x2="24.299" y1="18.747" y2="18.747" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="iJFHmWb" x1="26.189" x2="24.173" y1="20.025" y2="19.188" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="iTqYocd" x1="22.438" x2="21.037" y1="25.568" y2="26.203" gradientUnits="userSpaceOnUse"><stop class="ckxh1ljog"/><stop offset="1" class="om1zr9boo"/></linearGradient><linearGradient id="ipaJeOc" x1="22.959" x2="22.854" y1="28.106" y2="28.024" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="iiNKhod" x1="23.357" x2="23.604" y1="8.43" y2="7.993" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="iSDxsPb" x1="24.58" x2="22.393" y1="16" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="af5ecjb0e"/><stop offset="1" class="bg5vqlb1m"/></linearGradient><linearGradient id="i7iqcFd" x1="13.875" x2="14.5" y1="17.042" y2="18.041" gradientUnits="userSpaceOnUse"><stop class="eizi_gdki"/><stop offset="1" class="pbgm9vhci"/></linearGradient><linearGradient id="iNqt4Yb" x1="19.83" x2="20.799" y1="20.29" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iOFXx8c" x1="22.801" x2="22.801" y1="16.875" y2="18.313" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="i7WfFTc" x1="23.994" x2="24.225" y1="18.403" y2="17.958" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="io6aCdd" x1="15.315" x2="15.649" y1="11.899" y2="11.547" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="i7oc0qb" x1="15.523" x2="15.691" y1="11.47" y2="11.268" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iJIwGpe" x1="15.789" x2="15.975" y1="11.074" y2="10.847" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="iWzE1pb" x1="24.643" x2="24.322" y1="10.026" y2="9.782" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iRlqTmc" x1="23.189" x2="23.627" y1="10.579" y2="10.868" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="iPJSHZb" x1="16.207" x2="16.397" y1="10.846" y2="10.65" gradientUnits="userSpaceOnUse"><stop offset=".002" class="pktfr7bne"/><stop offset="1" class="xgvx5wb1m"/></linearGradient><linearGradient id="i4jo5ce" x1="22.908" x2="22.783" y1="14.907" y2="13.985" gradientUnits="userSpaceOnUse"><stop class="wd5xhxb1x"/><stop offset="1" class="r_k29qxtj"/></linearGradient><filter id="iKDjXne" width="8.743" height="7.346" x="1.654" y="23.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_861" result="effect2_innerShadow_4002_861"/></filter><filter id="ikG50KR" width="4.276" height="5.599" x="13.043" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_861" stdDeviation=".375"/></filter><filter id="iTBVMEc" width="6.514" height="7.799" x="17.846" y="6.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.721569 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="idk10rt" width="3.383" height="4.772" x="18.714" y="7.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_861" stdDeviation=".15"/></filter><filter id="ij74i1d" width="3.479" height="7.738" x="13.618" y="2.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="i5KNQvc" width="2.822" height="15.029" x="18.984" y="2.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iIx3z8c" width="4.68" height="4.407" x="21.69" y="7.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.423529 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.670588 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_861" result="effect2_innerShadow_4002_861"/></filter><filter id="i1ki0qb" width="2.054" height="2.454" x="25.067" y="9.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.615686 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iboNeJb" width="5.316" height="9.197" x="18.453" y="20.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.639216 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iQU8OCc" width="5.527" height="3.544" x="18.662" y="18.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iCIBhie" width="9.577" height="5.489" x="9.343" y="15.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.47451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iC3tBBe" width="6.672" height="5.002" x="17.83" y="15.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="i069C1h" width="6.922" height="5.002" x="17.83" y="15.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iq96zFc" width="2.568" height="3.646" x="9.32" y="17.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iHLhIED" width="4.913" height="4.647" x="23.084" y="5.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="ilDjvyA" width="1.588" height="1.361" x="24.746" y="7.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="ikBi1Jc" width="6.514" height="4.796" x="15.307" y="10.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_861"/></filter><filter id="iGcMI9g" width="3.862" height="3.738" x="15.944" y="10.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_861" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-climbing-medium-light" /></template>
<style>
.a0px9dj6c {
  stop-color: var(--svg-color--c3958d, #C3958D);
}

.af5ecjb0e {
  stop-color: var(--svg-color--ff712f, #FF712F);
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.apb0ltxnb {
  d: path("m18.123 15.551l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.bd7clsboy {
  d: path("m23.528 8.538l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.bg5vqlb1m {
  stop-color: var(--svg-color--ff2f0b, #FF2F0B);
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bn_1vkbwm {
  stop-color: var(--svg-color--f52715, #F52715);
  stop-opacity: 0;
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.bxjhn945r {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M15.463 10.111a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.bylttzbhe {
  stop-color: var(--svg-color--bf7f81, #BF7F81);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c88tyqz5u {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.478 10.158l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.cflw04u6i {
  stroke: var(--svg-color--e9b397, #E9B397);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.594 11.232l2.562 2.437");
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.ckxh1ljog {
  stop-color: var(--svg-color--f0bea1, #F0BEA1);
}

.czdn7vy6a {
  stop-color: var(--svg-color--b9745e, #B9745E);
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.d7aonq0wf {
  stop-color: var(--svg-color--d4997b, #D4997B);
}

.db1j3cbeu {
  stop-color: var(--svg-color--cb7a6a, #CB7A6A);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.diqc8voui {
  d: path("m22.322 13.094l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.101-1.765c-.317-.172-1.026-.28-1.399-.16s-.73.663-.883 1.09");
}

.dlvk5ybil {
  fill-rule: evenodd;
  d: path("M24.373 18.105c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e7o2u97gd {
  stop-color: var(--svg-color--f5c4a4, #F5C4A4);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eizi_gdki {
  stop-color: var(--svg-color--dca888, #DCA888);
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.euzvt6bws {
  d: path("M20.182 7.07c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.exhdqvblc {
  d: path("M14.89 10.342a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.f_1v57bhd {
  stop-color: var(--svg-color--d59b81, #D59B81);
}

.f1q29qbun {
  fill-rule: evenodd;
  d: path("M24.184 19.154a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.f7ds2glhm {
  stop-color: var(--svg-color--bf7f81, #BF7F81);
  stop-opacity: 0;
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.ft5dv1b6b {
  fill: none;
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.g8vkilb5t {
  d: path("M14.663 11.39a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.ghwh3eklg {
  stop-color: var(--svg-color--a46f70, #A46F70);
  stop-opacity: 0;
}

.gk9uazn2k {
  stop-color: var(--svg-color--b9745e, #B9745E);
  stop-opacity: 0;
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gpobzabhu {
  d: path("M2.054 30.141v-8.953l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.112 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.556l5 4.753z");
}

.gppwtlz2l {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.791 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.gro4u4t-y {
  stop-color: var(--svg-color--d19f82, #D19F82);
}

.gtns2tbea {
  cx: 23.462px;
  cy: 8.074px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.hecffrsxz {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.054 23.196v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.523c-.065-.141-.186-.451-.371-.924l-.285-.725c-.322-.816-.953-1.219-1.437-1.422z");
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.i5u7mbb_e {
  fill-rule: evenodd;
  d: path("M20.77 15.938a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.iecr_084e {
  d: path("m19.162 20.854l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ilft87v6y {
  stop-color: var(--svg-color--f8736b, #F8736B);
  stop-opacity: 0;
}

.ilfznfb_s {
  fill: var(--svg-color--e5b699, #E5B699);
  d: path("m25.127 10.567l.488-1.367l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.203c-.2-.247-.133-.588-.074-.727");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j14n23bil {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M14.663 11.39a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jfz0xgwum {
  stop-color: var(--svg-color--e2452b, #E2452B);
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jonyfxbku {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.502 7.946c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k2u_13bdd {
  stop-color: var(--svg-color--e2452b, #E2452B);
  stop-opacity: 0;
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kg1ehzbwj {
  stop-color: var(--svg-color--f5c4a4, #F5C4A4);
}

.kjz5zrf_f {
  fill: var(--svg-color--ce9087, #CE9087);
  d: path("m18.893 21.141l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.kqp9fdbzy {
  stop-color: var(--svg-color--e8bb9d, #E8BB9D);
  stop-opacity: 0;
}

.kr3h2mtpz {
  d: path("m22.738 26.345l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.ks1_esbqd {
  fill-rule: evenodd;
  d: path("M23.362 13.956c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.869z");
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l6j0rsiac {
  d: path("m18.893 21.141l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.l9mu7xbce {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.412 8.636a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32L25.06 8.67a.25.25 0 0 1 .352-.033");
}

.lxwwy-b-c {
  d: path("M24.809 7.584a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.m_hdbfh7v {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M22.375 9.336a.1.1 0 0 1 .139-.029c.085.056.25.103.52.041a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.mddv4hbgz {
  d: path("M15.463 10.111a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mqbi9fb1c {
  d: path("m11.838 20.2l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
}

.mwbu5sbnw {
  stop-color: var(--svg-color--4a4476, #4A4476);
}

.mzz_2wq-t {
  stop-color: var(--svg-color--c2bfc5, #C2BFC5);
}

.n_3yhnb8a {
  stop-color: var(--svg-color--958e9b, #958E9B);
  stop-opacity: 0;
}

.n_geicc-w {
  stop-color: var(--svg-color--f52715, #F52715);
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nk-mbmbtk {
  stop-color: var(--svg-color--e5a08a, #E5A08A);
}

.nku6vgp_t {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.791 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.npx64-mvq {
  stop-color: var(--svg-color--ff9057, #FF9057);
  stop-opacity: 0;
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nvv1klhll {
  stop-color: var(--svg-color--f8736b, #F8736B);
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.o6w7f1w7w {
  stop-color: var(--svg-color--ff722c, #FF722C);
}

.om1zr9boo {
  stop-color: var(--svg-color--f0bea1, #F0BEA1);
  stop-opacity: 0;
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p62i0qb1k {
  stop-color: var(--svg-color--cc9778, #CC9778);
}

.pa0ye030w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.264 7.99c.07.492.767 2.437 2.283 3.672");
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pbgm9vhci {
  stop-color: var(--svg-color--dca888, #DCA888);
  stop-opacity: 0;
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.pjyyhbb1f {
  d: path("M20.793 16.566c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.pktfr7bne {
  stop-color: var(--svg-color--d28f83, #D28F83);
}

.pl76o5b_i {
  stop-color: var(--svg-color--af6c57, #AF6C57);
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.q-jcn22bi {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.162 20.854l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qksuzsbug {
  stop-color: var(--svg-color--ff7857, #FF7857);
}

.qle60tltw {
  d: path("m20.791 16.57l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.qnag9id6v {
  d: path("m24.299 19.192l1.906.63v.73a.953.953 0 0 1-1.906 0z");
}

.qqtnb1ism {
  d: path("m21.218 15.18l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.qqun0kp3y {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.37 8.434l.053-.07c.073-.12.081-.25.019-.288c-.064-.038-.174.028-.247.148l-.035.071z");
}

.r_5s-tw4v {
  stop-color: var(--svg-color--e8bb9d, #E8BB9D);
}

.r_k29qxtj {
  stop-color: var(--svg-color--fb5139, #FB5139);
  stop-opacity: 0;
}

.r1g9oggar {
  stop-color: var(--svg-color--d9a288, #D9A288);
  stop-opacity: 0;
}

.r3ssxeblm {
  fill: var(--svg-color--dfa68f, #DFA68F);
  fill-rule: evenodd;
  d: path("m17.962 14.385l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.revn8gesq {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.738 26.345l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.rh20j3bdy {
  d: path("m25.127 10.567l.488-1.367l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.203c-.2-.247-.133-.588-.074-.727");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.se__e0blq {
  stop-color: var(--svg-color--ff7857, #FF7857);
  stop-opacity: 0;
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.tjcgz75aq {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M14.89 10.342a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.ub86ttbns {
  d: path("M14.738 10.857a.28.28 0 0 1 .367-.42l1.5 1.31l-.367.42z");
}

.ubnjkbb9g {
  d: path("M23.43 10.897h1.905v1.844H23.43z");
}

.ufi1sccsl {
  stop-color: var(--svg-color--bd7475, #BD7475);
}

.uph363bnf {
  fill: var(--svg-color--dfa690, #DFA690);
  d: path("m16.478 10.158l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.uxye37bbx {
  fill-rule: evenodd;
  d: path("M25.412 8.636a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32L25.06 8.67a.25.25 0 0 1 .352-.033");
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.v5ir-udep {
  fill: var(--svg-color--dfa48d, #DFA48D);
  d: path("M14.738 10.857a.28.28 0 0 1 .367-.42l1.5 1.31l-.367.42z");
}

.v5m-xebtg {
  stop-color: var(--svg-color--f94b3a, #F94B3A);
}

.v8ombmbjb {
  stop-color: var(--svg-color--d9a288, #D9A288);
}

.vgqexrbdw {
  d: path("M9.29 17.135a.93.93 0 0 1 .456-.698l-7.692 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.vrat0nbqn {
  d: path("M14.501 14.876L2.054 19.238V2.196h15.944c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.vrwnjxbrf {
  d: path("M9.918 2.196c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.196z");
}

.w_i4jlbaj {
  fill: var(--svg-color--dfb491, #DFB491);
  d: path("M20.182 7.07c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wbuujvb8l {
  d: path("M26.808 10.202L23.18 7.506a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.wd5xhxb1x {
  stop-color: var(--svg-color--e43e1c, #E43E1C);
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wxl7pfshq {
  stop-color: var(--svg-color--a46f70, #A46F70);
}

.wxwfcehps {
  d: path("M22.01 9.618c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x8-nb-ihc {
  stop-color: var(--svg-color--cf9388, #CF9388);
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xapik5b0z {
  stop-color: var(--svg-color--ff9057, #FF9057);
}

.xgvx5wb1m {
  stop-color: var(--svg-color--d28f83, #D28F83);
  stop-opacity: 0;
}

.xyrev7w3n {
  fill: var(--svg-color--d8a283, #D8A283);
  d: path("m18.123 15.551l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y46mnhndx {
  d: path("m16.568 12.45l-.06.426c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .291-.433l-.023-.033a.28.28 0 1 1 .455-.323l.106.146a.28.28 0 0 1 .5-.223l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.yoiyyhbuh {
  d: path("M13.638 2.152c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.z_c6qsb5g {
  cx: 25.146px;
  cy: 9.487px;
  r: 0.559px;
}

.z-4xjv8km {
  d: path("M18.984 2.196v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.196z");
}

.z1kr6xzoo {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.838 20.2l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.zach8zb-s {
  d: path("M22.15 8.43c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

</style>
