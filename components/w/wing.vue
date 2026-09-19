<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j6her-amu"/><path fill="url(#iT7buIc)" clip-rule="evenodd" class="axqmitjfa"/><path clip-rule="evenodd" class="u92y_yjfz"/><path fill="url(#i9CrMLS)" clip-rule="evenodd" class="nkdb1nk8w"/><path clip-rule="evenodd" class="djswo3ycm"/><path fill="url(#i4n5cdd)" clip-rule="evenodd" class="fet61ib7i"/><path fill="url(#iKteyJb)" clip-rule="evenodd" class="fet61ib7i"/><path clip-rule="evenodd" class="bb568-lvo"/><path fill="url(#iAB5OGd)" clip-rule="evenodd" class="n4-srdt9k"/><path fill="url(#itQcUxe)" clip-rule="evenodd" class="n4-srdt9k"/><path clip-rule="evenodd" class="qvqpytztd"/><path fill="url(#idKRN4d)" clip-rule="evenodd" class="dilfhzb9c"/><path fill="url(#i7XllGc)" clip-rule="evenodd" class="dilfhzb9c"/><path fill="url(#iRSSUdb)" clip-rule="evenodd" class="dilfhzb9c"/><path clip-rule="evenodd" class="k8kcwze6j"/><path fill="url(#izTTQNb)" clip-rule="evenodd" class="g-xsc6_wx"/><path fill="url(#ipEiIzc)" clip-rule="evenodd" class="g-xsc6_wx"/><path clip-rule="evenodd" class="dzii_9e6e"/><path fill="url(#idnwA2c)" clip-rule="evenodd" class="h108u7b0o"/><path fill="url(#iWKuNjc)" clip-rule="evenodd" class="h108u7b0o"/><path fill="url(#iux8ICd)" clip-rule="evenodd" class="h108u7b0o"/><path clip-rule="evenodd" class="crvzh8l5m"/><path fill="url(#iOH4Crd)" clip-rule="evenodd" class="c25d6cbvy"/><path clip-rule="evenodd" class="gp05z3-2j"/><path fill="url(#ipIynOc)" clip-rule="evenodd" class="ntbjjbcpa"/><path fill="url(#i7wjdQc)" clip-rule="evenodd" class="ntbjjbcpa"/><path fill="url(#iaAI4Kb)" clip-rule="evenodd" class="dgngatb-t"/><path fill="url(#iHQBmKd)" clip-rule="evenodd" class="dgngatb-t"/><ellipse fill="url(#iMQOfld)" class="jx-7bxbcb"/><ellipse fill="url(#ij7ySUb)" class="jx-7bxbcb"/><ellipse fill="url(#igMPvxe)" class="jx-7bxbcb"/><ellipse fill="url(#iRQNNud)" class="jx-7bxbcb"/><ellipse fill="url(#isIVJfb)" class="jx-7bxbcb"/><path clip-rule="evenodd" class="cnltd_e-d"/><path fill="url(#iu3hI4d)" clip-rule="evenodd" class="ojmqirgro"/><path fill="url(#iqoap0b)" clip-rule="evenodd" class="ojmqirgro"/><path fill="url(#iK1MaPb)" clip-rule="evenodd" class="ojmqirgro"/><path fill="url(#io6PVOb)" clip-rule="evenodd" class="ojmqirgro"/><path clip-rule="evenodd" class="x0ft7zbht"/><path fill="url(#iaVgdjb)" clip-rule="evenodd" class="dtbc3mbxy"/><path fill="url(#ihABjpb)" clip-rule="evenodd" class="dtbc3mbxy"/><path fill="url(#iEOnsxd)" clip-rule="evenodd" class="dtbc3mbxy"/><path fill="url(#i7Wv6xe)" clip-rule="evenodd" class="dtbc3mbxy"/><path clip-rule="evenodd" class="ov9ky_ndl"/><path fill="url(#iUrr16d)" clip-rule="evenodd" class="ja0cfdbqm"/><path fill="url(#ieNn1Jh)" clip-rule="evenodd" class="ja0cfdbqm"/><path fill="url(#i8iPEHb)" clip-rule="evenodd" class="ja0cfdbqm"/><path fill="url(#ie3wMDc)" clip-rule="evenodd" class="ja0cfdbqm"/><defs><radialGradient id="iT7buIc" cx="0" cy="0" r="1" gradientTransform="rotate(144.103 -.552 15.083)scale(8.10117 20.8143)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oe-6eclwq"/><stop offset=".254" class="syyo7lzow"/></radialGradient><radialGradient id="i9CrMLS" cx="0" cy="0" r="1" gradientTransform="rotate(146.8 .569 14.015)scale(7.54398 27.129)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="fxxuhqb6m"/><stop offset=".195" class="bxv6wdbvj"/></radialGradient><radialGradient id="i4n5cdd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53123 4.34377 -23.68027 -24.7022 10.375 23.25)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="ntp05bcov"/><stop offset=".195" class="g550eebzg"/></radialGradient><radialGradient id="iKteyJb" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 2.642 14.232)scale(7.58622 14.7627)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="vboxrhebh"/><stop offset=".758" class="svt8jmbut"/></radialGradient><radialGradient id="iAB5OGd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31002 4.65627 -23.90133 -16.99082 12.904 21.781)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="fxxuhqb6m"/><stop offset=".296" class="bxv6wdbvj"/></radialGradient><radialGradient id="itQcUxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31248 3.5586 -8.5822 3.1653 7.343 17.969)" gradientUnits="userSpaceOnUse"><stop class="rto6q0q1c"/><stop offset="1" class="nb_7xl99r"/></radialGradient><radialGradient id="idKRN4d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5937 5.75002 -30.38383 -13.70542 15.594 19.156)" gradientUnits="userSpaceOnUse"><stop offset=".089" class="ntp05bcov"/><stop offset=".285" class="g550eebzg"/></radialGradient><radialGradient id="i7XllGc" cx="0" cy="0" r="1" gradientTransform="rotate(118.043 5.273 12.816)scale(14.0919 18.7716)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="vboxrhebh"/><stop offset=".727" class="svt8jmbut"/></radialGradient><radialGradient id="iRSSUdb" cx="0" cy="0" r="1" gradientTransform="rotate(125.64 .023 11.03)scale(4.07594 2.01161)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="b-aqibcpw"/><stop offset="1" class="sgsbkmp0p"/></radialGradient><radialGradient id="izTTQNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91476 5.98421 -15.52913 -4.96882 18.281 13.938)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fxxuhqb6m"/><stop offset=".687" class="bxv6wdbvj"/></radialGradient><radialGradient id="ipEiIzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09376 -1.65625 4.0747 -2.69085 11.156 15.531)" gradientUnits="userSpaceOnUse"><stop class="rto6q0q1c"/><stop offset="1" class="nb_7xl99r"/></radialGradient><radialGradient id="idnwA2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.06252 5.75 -17.81725 -.19374 18.906 10.688)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="mr8y7oopc"/><stop offset=".687" class="zki-6ob1k"/></radialGradient><radialGradient id="iWKuNjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7524 8.29996 -17.73003 -3.74341 18.502 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="vboxrhebh"/><stop offset=".727" class="svt8jmbut"/></radialGradient><radialGradient id="iux8ICd" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 1.1875 -2.26861 1.791 12.938 13.907)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="ntp05bcov"/><stop offset="1" class="g550eebzg"/></radialGradient><radialGradient id="iOH4Crd" cx="0" cy="0" r="1" gradientTransform="matrix(.568 7.39336 -23.28708 1.78902 18.003 5.839)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="g2_nrkgiu"/><stop offset=".687" class="zn3mb2bxi"/></radialGradient><radialGradient id="ipIynOc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09373 5.65626 -20.8224 4.02635 18.843 3.188)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="wwibar8gw"/><stop offset=".73" class="u77i8xjyb"/></radialGradient><radialGradient id="i7wjdQc" cx="0" cy="0" r="1" gradientTransform="rotate(78.018 7.622 13.313)scale(8.881 22.8495)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="su_b9ibcn"/><stop offset=".621" class="fnqfq0xcl"/></radialGradient><radialGradient id="ij7ySUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 8.6875 -7.90583 -1.36503 11.063 11.313)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="g4tkzqb2k"/><stop offset=".642" class="drc-mg69z"/></radialGradient><radialGradient id="iRQNNud" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 1.28125 -5.2117 -.12712 9.281 15.5)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="dcm7ltbwv"/><stop offset="1" class="rjf768bpi"/></radialGradient><radialGradient id="isIVJfb" cx="0" cy="0" r="1" gradientTransform="rotate(87.578 -.33 10.357)scale(5.1765 5.18112)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="ti6210b_p"/><stop offset="1" class="d1zq-o4ps"/></radialGradient><radialGradient id="iu3hI4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.99727 .19888 -.71751 -3.598 8.574 16.573)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="c7ns-v5ak"/><stop offset=".968" class="rn736hbxb"/></radialGradient><radialGradient id="iqoap0b" cx="0" cy="0" r="1" gradientTransform="rotate(173.721 4.561 8.512)scale(3.53382 5.24695)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="rn736hbxb"/><stop offset=".945" class="c7ns-v5ak"/></radialGradient><radialGradient id="io6PVOb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71354 9.34571 -2.0906 .607 5.54 10.796)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="i39ilyala"/><stop offset=".959" class="b2hfxibcx"/></radialGradient><radialGradient id="iaVgdjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80455 .61586 -2.22902 -2.91196 9.078 15.368)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="c7ns-v5ak"/><stop offset=".968" class="rn736hbxb"/></radialGradient><radialGradient id="ihABjpb" cx="0" cy="0" r="1" gradientTransform="rotate(147.583 3.038 8.823)scale(3.52073 5.2449)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="rn736hbxb"/><stop offset=".945" class="c7ns-v5ak"/></radialGradient><radialGradient id="i7Wv6xe" cx="0" cy="0" r="1" gradientTransform="matrix(6.64099 7.19531 -1.71042 1.57865 3.787 11.475)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="i39ilyala"/><stop offset=".967" class="b2hfxibcx"/></radialGradient><radialGradient id="iUrr16d" cx="0" cy="0" r="1" gradientTransform="rotate(123.69 .991 9.716)scale(1.01406 3.6657)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="c7ns-v5ak"/><stop offset=".968" class="rn736hbxb"/></radialGradient><radialGradient id="ieNn1Jh" cx="0" cy="0" r="1" gradientTransform="rotate(128.699 2.123 9.134)scale(3.52367 5.24282)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="rn736hbxb"/><stop offset=".945" class="c7ns-v5ak"/></radialGradient><radialGradient id="i8iPEHb" cx="0" cy="0" r="1" gradientTransform="matrix(8.60937 4.65626 -1.10818 2.04901 3.36 12.313)" gradientUnits="userSpaceOnUse"><stop offset=".942" class="i39ilyala"/><stop offset=".977" class="b2hfxibcx"/></radialGradient><linearGradient id="iaAI4Kb" x1="7.219" x2="4.25" y1="13.125" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="qpy7gmb_s"/><stop offset="1" class="on4-jezcl"/></linearGradient><linearGradient id="iHQBmKd" x1="4.094" x2="6.063" y1="22.5" y2="22.828" gradientUnits="userSpaceOnUse"><stop class="slbu64o4f"/><stop offset=".11" class="c91h5-bay"/><stop offset=".89" class="opr-2bb0a"/><stop offset="1" class="zd6edsbzm"/></linearGradient><linearGradient id="iMQOfld" x1="13.719" x2="7.75" y1="8.063" y2="12.969" gradientUnits="userSpaceOnUse"><stop offset=".03" class="o4t1s_zzn"/><stop offset=".588" class="rvtv-pp4m"/><stop offset="1" class="ywze60b8u"/></linearGradient><linearGradient id="igMPvxe" x1="12.875" x2="9.219" y1="14.813" y2="10.744" gradientUnits="userSpaceOnUse"><stop class="mrdbv641s"/><stop offset=".62" class="t52-xox8h"/></linearGradient><linearGradient id="iK1MaPb" x1="5.281" x2="8.498" y1="17.594" y2="18.197" gradientUnits="userSpaceOnUse"><stop offset=".373" class="umveeubqb"/><stop offset=".855" class="fd64c1t-w"/></linearGradient><linearGradient id="iEOnsxd" x1="5.039" x2="8.386" y1="15.206" y2="17.974" gradientUnits="userSpaceOnUse"><stop offset=".373" class="umveeubqb"/><stop offset=".855" class="fd64c1t-w"/></linearGradient><linearGradient id="ie3wMDc" x1="5.75" x2="9.81" y1="15.438" y2="16.974" gradientUnits="userSpaceOnUse"><stop offset=".373" class="umveeubqb"/><stop offset=".855" class="fd64c1t-w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wing" /></template>
<style>
.axqmitjfa {
  fill-rule: evenodd;
  d: path("M7.986 22.909c.539-.535.605-1.4.128-2.006a1.486 1.486 0 0 0-2.1-.234a2.7 2.7 0 0 0-.625.77c-.137.242-.26.514-.367.796c-.217.566-.41 1.262-.546 2.013c-.266 1.47-.35 3.375.241 5.05a1.48 1.48 0 0 0 1.909.9a1.52 1.52 0 0 0 .91-1.928c-.346-.983-.337-2.297-.118-3.508a8.4 8.4 0 0 1 .393-1.466c.071-.185.132-.31.173-.382zm.018-.03l.009-.012z");
}

.b-aqibcpw {
  stop-color: var(--svg-color--776b83, #776B83);
}

.b2hfxibcx {
  stop-color: var(--svg-color--9f91ae, #9F91AE);
}

.bb568-lvo {
  fill: var(--svg-color--bac, #BAC);
  fill-rule: evenodd;
  d: path("M20.124 27.06c-.346 1.057-1.472 1.638-2.514 1.297C9.073 25.57 6.395 19.486 5.8 17.027a2.03 2.03 0 0 1 1.46-2.444a1.97 1.97 0 0 1 2.404 1.455c.343 1.418 2.23 6.215 9.199 8.491c1.042.34 1.607 1.474 1.26 2.53");
}

.bxv6wdbvj {
  stop-color: var(--svg-color--afa2bd, #AFA2BD);
  stop-opacity: 0;
}

.c25d6cbvy {
  fill-rule: evenodd;
  d: path("M29.669 6.958a3 3 0 0 1-1.176 4.077c-4.493 2.48-9.294 2.794-12.87 2.532c-3.537-.259-6.217-1.108-6.754-1.337a3 3 0 1 1 2.354-5.519q-.03-.013.065.017c.383.115 2.231.669 4.773.855c2.926.214 6.428-.087 9.532-1.8a3 3 0 0 1 4.076 1.175");
}

.c7ns-v5ak {
  stop-color: var(--svg-color--9589a2, #9589A2);
}

.c91h5-bay {
  stop-color: var(--svg-color--e8e3ef, #E8E3EF);
  stop-opacity: 0;
}

.cnltd_e-d {
  fill: var(--svg-color--b8a7ca, #B8A7CA);
  fill-rule: evenodd;
  d: path("M8.278 14.104c-.136-.166-.587-1.39-1.08-.747a1 1 0 0 0-.105.176a3 3 0 0 0-.067.157a5 5 0 0 0-.148.441a7 7 0 0 0-.25 1.39c-.09 1.113.052 2.576.947 3.974a.658.658 0 1 0 1.108-.71c-.697-1.089-.818-2.241-.744-3.16c.037-.457.122-.849.203-1.13a4 4 0 0 1 .136-.39");
}

.crvzh8l5m {
  fill: var(--svg-color--c2b5d1, #C2B5D1);
  fill-rule: evenodd;
  d: path("M29.669 6.958a3 3 0 0 1-1.176 4.077c-4.493 2.48-9.294 2.794-12.87 2.532c-3.537-.259-6.217-1.108-6.754-1.337a3 3 0 1 1 2.354-5.519q-.03-.013.065.017c.383.115 2.231.669 4.773.855c2.926.214 6.428-.087 9.532-1.8a3 3 0 0 1 4.076 1.175");
}

.d1zq-o4ps {
  stop-color: var(--svg-color--9c8fa8, #9C8FA8);
}

.dcm7ltbwv {
  stop-color: var(--svg-color--9e90ad, #9E90AD);
}

.dgngatb-t {
  fill-rule: evenodd;
  d: path("M7.203 9.4a1 1 0 0 1 .828 1.146l-3.04 18.86a1 1 0 0 1-1.974-.318l3.04-18.86A1 1 0 0 1 7.202 9.4");
}

.dilfhzb9c {
  fill-rule: evenodd;
  d: path("M23.72 22.985c.054 1.112-.79 2.063-1.884 2.125c-5.469.309-9.403-2.363-11.9-5.026a21.2 21.2 0 0 1-2.783-3.739c-.31-.527-.548-.987-.716-1.339c-.136-.283-.294-.636-.364-.889c-.296-1.07.32-2.186 1.375-2.493a1.97 1.97 0 0 1 2.446 1.381l-.023-.08c.001 0 .037.091.137.3c.122.255.307.615.558 1.042a17.2 17.2 0 0 0 2.251 3.027c1.998 2.13 4.883 4.013 8.823 3.79c1.095-.061 2.026.79 2.08 1.901");
}

.djswo3ycm {
  fill: var(--svg-color--8a7c98, #8A7C98);
  fill-rule: evenodd;
  d: path("M14.974 29.465a1.98 1.98 0 0 1-2.791.38c-3.473-2.696-5.02-5.502-5.71-8c-.338-1.22-.455-2.313-.522-3.174c-.023-.293-.04-.532-.053-.73c-.033-.475-.05-.72-.097-.913a2.03 2.03 0 0 1 1.46-2.444a1.97 1.97 0 0 1 2.405 1.455c.135.56.184 1.294.223 1.884l.027.398c.059.754.151 1.553.388 2.41c.457 1.653 1.509 3.734 4.319 5.915c.868.674 1.025 1.936.35 2.82");
}

.drc-mg69z {
  stop-color: var(--svg-color--e7e4ec, #E7E4EC);
}

.dtbc3mbxy {
  fill-rule: evenodd;
  d: path("M7.073 12.562a.66.66 0 0 1 .658.66c.002.041.05.722.376 1.567c.334.864.941 1.852 2.041 2.52a.659.659 0 0 1-.682 1.126c-1.422-.864-2.183-2.129-2.585-3.17c-.399-1.032-.466-1.893-.466-2.045c0-.363.295-.658.658-.658");
}

.dzii_9e6e {
  fill: var(--svg-color--8d8299, #8D8299);
  fill-rule: evenodd;
  d: path("M12.82 9.495a2.5 2.5 0 0 0-2.893-.536a2.494 2.494 0 0 0-1.16 3.336c.18.372.418.623.466.673l.005.005c.09.096.176.175.24.23c.132.116.277.23.422.337c.294.216.675.47 1.13.737a21.3 21.3 0 0 0 3.735 1.717c3.104 1.085 7.434 1.83 12.302.569a2.49 2.49 0 0 0 1.777-3.049a2.51 2.51 0 0 0-3.053-1.796c-3.678.954-6.975.4-9.402-.448a16 16 0 0 1-2.841-1.302a9 9 0 0 1-.728-.473");
}

.fd64c1t-w {
  stop-color: var(--svg-color--cab9db, #CAB9DB);
  stop-opacity: 0;
}

.fet61ib7i {
  fill-rule: evenodd;
  d: path("M14.974 29.465a1.98 1.98 0 0 1-2.791.38c-3.473-2.696-5.02-5.502-5.71-8c-.338-1.22-.455-2.313-.522-3.174c-.023-.293-.04-.532-.053-.73c-.033-.475-.05-.72-.097-.913a2.03 2.03 0 0 1 1.46-2.444a1.97 1.97 0 0 1 2.405 1.455c.135.56.184 1.294.223 1.884l.027.398c.059.754.151 1.553.388 2.41c.457 1.653 1.509 3.734 4.319 5.915c.868.674 1.025 1.936.35 2.82");
}

.fnqfq0xcl {
  stop-color: var(--svg-color--a99ab7, #A99AB7);
}

.ft5dv1b6b {
  fill: none;
}

.fxxuhqb6m {
  stop-color: var(--svg-color--afa2bd, #AFA2BD);
}

.g-xsc6_wx {
  fill-rule: evenodd;
  d: path("M26.558 18.784c.112 1.386-.905 2.592-2.273 2.694c-5.057.376-8.801-1.215-11.3-2.767c-1.073-.667-1.93-1.337-2.488-1.773l-.207-.162a2.5 2.5 0 0 1-.61-.212a2.546 2.546 0 0 1-1.149-3.372c.17-.352.457-.75.918-1.054a2.6 2.6 0 0 1 1.352-.423a2.9 2.9 0 0 1 1.4.338c.405.207.814.524 1.058.713l.018.014l.248.193c.56.438 1.204.94 2.031 1.454c1.855 1.152 4.566 2.312 8.324 2.032c1.368-.102 2.567.94 2.678 2.325");
}

.g2_nrkgiu {
  stop-color: var(--svg-color--b3a9bf, #B3A9BF);
}

.g4tkzqb2k {
  stop-color: var(--svg-color--e7e4ec, #E7E4EC);
  stop-opacity: 0;
}

.g550eebzg {
  stop-color: var(--svg-color--776a85, #776A85);
  stop-opacity: 0;
}

.gp05z3-2j {
  fill: var(--svg-color--c4b7d3, #C4B7D3);
  fill-rule: evenodd;
  d: path("M29.756 2.925a1.5 1.5 0 0 1-.428 2.078C25.383 7.6 20.743 8.64 17.13 9.048a40 40 0 0 1-5.97.22q-.258-.011-.406-.019l-.117-.006h.016a1.5 1.5 0 0 1 0-3q.056 0 .226.008c1.585.072 10.388.47 16.8-3.754a1.5 1.5 0 0 1 2.078.428");
}

.h108u7b0o {
  fill-rule: evenodd;
  d: path("M12.82 9.495a2.5 2.5 0 0 0-2.893-.536a2.494 2.494 0 0 0-1.16 3.336c.18.372.418.623.466.673l.005.005c.09.096.176.175.24.23c.132.116.277.23.422.337c.294.216.675.47 1.13.737a21.3 21.3 0 0 0 3.735 1.717c3.104 1.085 7.434 1.83 12.302.569a2.49 2.49 0 0 0 1.777-3.049a2.51 2.51 0 0 0-3.053-1.796c-3.678.954-6.975.4-9.402-.448a16 16 0 0 1-2.841-1.302a9 9 0 0 1-.728-.473");
}

.i39ilyala {
  stop-color: var(--svg-color--9f91ae, #9F91AE);
  stop-opacity: 0;
}

.j6her-amu {
  fill: var(--svg-color--9688a5, #9688A5);
  fill-rule: evenodd;
  d: path("M7.986 22.909c.539-.535.605-1.4.128-2.006a1.486 1.486 0 0 0-2.1-.234a2.7 2.7 0 0 0-.625.77c-.137.242-.26.514-.367.796c-.217.566-.41 1.262-.546 2.013c-.266 1.47-.35 3.375.241 5.05a1.48 1.48 0 0 0 1.909.9a1.52 1.52 0 0 0 .91-1.928c-.346-.983-.337-2.297-.118-3.508a8.4 8.4 0 0 1 .393-1.466c.071-.185.132-.31.173-.382zm.018-.03l.009-.012z");
}

.ja0cfdbqm {
  fill-rule: evenodd;
  d: path("M6.87 12.26c.351-.09.71.122.8.475l-.007-.029l.036.084c.034.074.086.18.158.309c.143.257.36.596.658.95c.596.709 1.492 1.446 2.75 1.721a.659.659 0 0 1-.282 1.287c-1.624-.356-2.755-1.305-3.474-2.16a7.5 7.5 0 0 1-.8-1.157a6 6 0 0 1-.205-.4a2 2 0 0 1-.107-.278a.66.66 0 0 1 .473-.801");
}

.jx-7bxbcb {
  cx: 10.502px;
  cy: 10.744px;
  rx: 4.501px;
  ry: 4.502px;
}

.k8kcwze6j {
  fill: var(--svg-color--c0b1cf, #C0B1CF);
  fill-rule: evenodd;
  d: path("M26.558 18.784c.112 1.386-.905 2.592-2.273 2.694c-5.057.376-8.801-1.215-11.3-2.767c-1.073-.667-1.93-1.337-2.488-1.773l-.207-.162a2.5 2.5 0 0 1-.61-.212a2.546 2.546 0 0 1-1.149-3.372c.17-.352.457-.75.918-1.054a2.6 2.6 0 0 1 1.352-.423a2.9 2.9 0 0 1 1.4.338c.405.207.814.524 1.058.713l.018.014l.248.193c.56.438 1.204.94 2.031 1.454c1.855 1.152 4.566 2.312 8.324 2.032c1.368-.102 2.567.94 2.678 2.325");
}

.mr8y7oopc {
  stop-color: var(--svg-color--796e83, #796E83);
}

.mrdbv641s {
  stop-color: var(--svg-color--bca7d1, #BCA7D1);
}

.n4-srdt9k {
  fill-rule: evenodd;
  d: path("M20.124 27.06c-.346 1.057-1.472 1.638-2.514 1.297C9.073 25.57 6.395 19.486 5.8 17.027a2.03 2.03 0 0 1 1.46-2.444a1.97 1.97 0 0 1 2.404 1.455c.343 1.418 2.23 6.215 9.199 8.491c1.042.34 1.607 1.474 1.26 2.53");
}

.nb_7xl99r {
  stop-color: var(--svg-color--a29aac, #A29AAC);
  stop-opacity: 0;
}

.nkdb1nk8w {
  fill-rule: evenodd;
  d: path("M10.484 29.713a1.493 1.493 0 0 1-2.1.26c-1.425-1.128-2.283-3.119-2.717-4.671c-.228-.813-.372-1.62-.409-2.298a4.7 4.7 0 0 1 .043-1.025c.04-.24.167-.871.712-1.307c.65-.52 1.59-.415 2.1.234a1.51 1.51 0 0 1 .127 1.67q-.003.085.004.237c.023.411.12.997.302 1.65c.386 1.378 1.028 2.608 1.699 3.138c.646.511.753 1.457.24 2.112M8.25 22.46c.006-.038.01-.028-.002.012z");
}

.ntbjjbcpa {
  fill-rule: evenodd;
  d: path("M29.756 2.925a1.5 1.5 0 0 1-.428 2.078C25.383 7.6 20.743 8.64 17.13 9.048a40 40 0 0 1-5.97.22q-.258-.011-.406-.019l-.117-.006h.016a1.5 1.5 0 0 1 0-3q.056 0 .226.008c1.585.072 10.388.47 16.8-3.754a1.5 1.5 0 0 1 2.078.428");
}

.ntp05bcov {
  stop-color: var(--svg-color--776a85, #776A85);
}

.o4t1s_zzn {
  stop-color: var(--svg-color--c2b6cf, #C2B6CF);
}

.oe-6eclwq {
  stop-color: var(--svg-color--897e95, #897E95);
}

.ojmqirgro {
  fill-rule: evenodd;
  d: path("M8.278 14.104c-.136-.166-.587-1.39-1.08-.747a1 1 0 0 0-.105.176a3 3 0 0 0-.067.157a5 5 0 0 0-.148.441a7 7 0 0 0-.25 1.39c-.09 1.113.052 2.576.947 3.974a.658.658 0 1 0 1.108-.71c-.697-1.089-.818-2.241-.744-3.16c.037-.457.122-.849.203-1.13a4 4 0 0 1 .136-.39");
}

.on4-jezcl {
  stop-color: var(--svg-color--cebee0, #CEBEE0);
}

.opr-2bb0a {
  stop-color: var(--svg-color--a89ab7, #A89AB7);
  stop-opacity: 0;
}

.ov9ky_ndl {
  fill: var(--svg-color--b8a7ca, #B8A7CA);
  fill-rule: evenodd;
  d: path("M6.87 12.26c.351-.09.71.122.8.475l-.007-.029l.036.084c.034.074.086.18.158.309c.143.257.36.596.658.95c.596.709 1.492 1.446 2.75 1.721a.659.659 0 0 1-.282 1.287c-1.624-.356-2.755-1.305-3.474-2.16a7.5 7.5 0 0 1-.8-1.157a6 6 0 0 1-.205-.4a2 2 0 0 1-.107-.278a.66.66 0 0 1 .473-.801");
}

.qpy7gmb_s {
  stop-color: var(--svg-color--c9bada, #C9BADA);
}

.qvqpytztd {
  fill: var(--svg-color--8d7f9a, #8D7F9A);
  fill-rule: evenodd;
  d: path("M23.72 22.985c.054 1.112-.79 2.063-1.884 2.125c-5.469.309-9.403-2.363-11.9-5.026a21.2 21.2 0 0 1-2.783-3.739c-.31-.527-.548-.987-.716-1.339c-.136-.283-.294-.636-.364-.889c-.296-1.07.32-2.186 1.375-2.493a1.97 1.97 0 0 1 2.446 1.381l-.023-.08c.001 0 .037.091.137.3c.122.255.307.615.558 1.042a17.2 17.2 0 0 0 2.251 3.027c1.998 2.13 4.883 4.013 8.823 3.79c1.095-.061 2.026.79 2.08 1.901");
}

.rjf768bpi {
  stop-color: var(--svg-color--b6a4c9, #B6A4C9);
  stop-opacity: 0;
}

.rn736hbxb {
  stop-color: var(--svg-color--9589a2, #9589A2);
  stop-opacity: 0;
}

.rto6q0q1c {
  stop-color: var(--svg-color--a29aac, #A29AAC);
}

.rvtv-pp4m {
  stop-color: var(--svg-color--cab8df, #CAB8DF);
}

.sgsbkmp0p {
  stop-color: var(--svg-color--776b83, #776B83);
  stop-opacity: 0;
}

.slbu64o4f {
  stop-color: var(--svg-color--e8e3ef, #E8E3EF);
}

.su_b9ibcn {
  stop-color: var(--svg-color--ad9fbc, #AD9FBC);
  stop-opacity: 0;
}

.svt8jmbut {
  stop-color: var(--svg-color--7d6f8b, #7D6F8B);
}

.syyo7lzow {
  stop-color: var(--svg-color--897e95, #897E95);
  stop-opacity: 0;
}

.t52-xox8h {
  stop-color: var(--svg-color--bca7d1, #BCA7D1);
  stop-opacity: 0;
}

.ti6210b_p {
  stop-color: var(--svg-color--c4afda, #C4AFDA);
  stop-opacity: 0;
}

.u77i8xjyb {
  stop-color: var(--svg-color--bdb9c2, #BDB9C2);
  stop-opacity: 0;
}

.u92y_yjfz {
  fill: var(--svg-color--bfb1cf, #BFB1CF);
  fill-rule: evenodd;
  d: path("M10.484 29.713a1.493 1.493 0 0 1-2.1.26c-1.425-1.128-2.283-3.119-2.717-4.671c-.228-.813-.372-1.62-.409-2.298a4.7 4.7 0 0 1 .043-1.025c.04-.24.167-.871.712-1.307c.65-.52 1.59-.415 2.1.234a1.51 1.51 0 0 1 .127 1.67q-.003.085.004.237c.023.411.12.997.302 1.65c.386 1.378 1.028 2.608 1.699 3.138c.646.511.753 1.457.24 2.112M8.25 22.46c.006-.038.01-.028-.002.012z");
}

.umveeubqb {
  stop-color: var(--svg-color--cbbadc, #CBBADC);
}

.vboxrhebh {
  stop-color: var(--svg-color--8a789b, #8A789B);
  stop-opacity: 0;
}

.wwibar8gw {
  stop-color: var(--svg-color--bdb9c2, #BDB9C2);
}

.x0ft7zbht {
  fill: var(--svg-color--b8a7ca, #B8A7CA);
  fill-rule: evenodd;
  d: path("M7.073 12.562a.66.66 0 0 1 .658.66c.002.041.05.722.376 1.567c.334.864.941 1.852 2.041 2.52a.659.659 0 0 1-.682 1.126c-1.422-.864-2.183-2.129-2.585-3.17c-.399-1.032-.466-1.893-.466-2.045c0-.363.295-.658.658-.658");
}

.ywze60b8u {
  stop-color: var(--svg-color--c9b9da, #C9B9DA);
}

.zd6edsbzm {
  stop-color: var(--svg-color--a89ab7, #A89AB7);
}

.zki-6ob1k {
  stop-color: var(--svg-color--796e83, #796E83);
  stop-opacity: 0;
}

.zn3mb2bxi {
  stop-color: var(--svg-color--b3a9bf, #B3A9BF);
  stop-opacity: 0;
}

</style>
