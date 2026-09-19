<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9daEDb)" class="rv1nhib-j"/><path fill="url(#i0ieRrd)" class="ac612il1b"/><path fill="url(#iSsChBd)" class="u_9wfp45e"/><path fill="url(#i5dAJWd)" class="f_53usb0i"/><path fill="url(#iuZt1ie)" class="k5za1xbln"/><path clip-rule="evenodd" class="gbpj3_blb"/><path fill="url(#iEvptab)" class="rv1nhib-j"/><path fill="url(#iThJFBd)" class="rv1nhib-j"/><path fill="url(#iBOTYxe)" class="rv1nhib-j"/><path fill="url(#iKBeg1d)" class="rv1nhib-j"/><path fill="url(#imxBFlc)" class="rv1nhib-j"/><path fill="url(#ijrw93b)" class="yj416jhwz"/><path fill="url(#ioqP4Zb)" class="yj416jhwz"/><path fill="url(#ikOTO6d)" class="yj416jhwz"/><g filter="url(#i0AnDrb)"><path fill="url(#iAUq5QC)" class="w9pzy0b1z"/></g><path fill="url(#iv3kHxb)" class="hkr_8nbou"/><path fill="url(#iyDTxfd)" class="hkr_8nbou"/><path fill="url(#itYyQxb)" class="hkr_8nbou"/><g filter="url(#itzXEDd)"><path fill="url(#iKQ1Fzb)" class="v8r_yhmkz"/></g><g filter="url(#isfy28d)"><path fill="url(#iZqvEvc)" class="f_53usb0i"/></g><path fill="url(#i4VjeKy)" class="k5za1xbln"/><path fill="url(#ijA0fKe)" clip-rule="evenodd" class="jqamszbes"/><path fill="url(#i1HeMPc)" clip-rule="evenodd" class="jqamszbes"/><g filter="url(#iD8djKb)"><path stroke="url(#ijOHbmc)" class="g2e_9kb9s"/></g><defs><linearGradient id="i9daEDb" x1="16.108" x2="16.108" y1="29.885" y2="19.752" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset="1" class="c3bch-exu"/></linearGradient><linearGradient id="i0ieRrd" x1="15.211" x2="7.089" y1="29.489" y2="24.8" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset="1" class="c3bch-exu"/></linearGradient><linearGradient id="iSsChBd" x1="18.769" x2="25.176" y1="28.108" y2="25.12" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tju132bmi"/><stop offset="1" class="c3bch-exu"/></linearGradient><linearGradient id="i5dAJWd" x1="16.234" x2="15.825" y1="2.092" y2="23.845" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset="1" class="v-bq8jb7v"/></linearGradient><linearGradient id="iuZt1ie" x1="16.113" x2="15.893" y1="7.28" y2="18.995" gradientUnits="userSpaceOnUse"><stop class="u-1se5bme"/><stop offset="1" class="xpg7qbdiy"/></linearGradient><linearGradient id="iEvptab" x1="16.108" x2="16.108" y1="29.885" y2="20.406" gradientUnits="userSpaceOnUse"><stop class="l9miucc0b"/><stop offset="1" class="sddv6hldr"/></linearGradient><linearGradient id="iThJFBd" x1="14.984" x2="15.609" y1="28.016" y2="27.969" gradientUnits="userSpaceOnUse"><stop class="y8f693b9e"/><stop offset="1" class="wnjx4wbjd"/></linearGradient><linearGradient id="iBOTYxe" x1="17.107" x2="16.609" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="y8f693b9e"/><stop offset="1" class="wnjx4wbjd"/></linearGradient><linearGradient id="iKBeg1d" x1="15.016" x2="15.453" y1="23.656" y2="23.672" gradientUnits="userSpaceOnUse"><stop class="lcl8i2bvp"/><stop offset="1" class="n4t4mlb3d"/></linearGradient><linearGradient id="ijrw93b" x1="12.633" x2="8.414" y1="24.8" y2="30.511" gradientUnits="userSpaceOnUse"><stop offset=".011" class="hinb-sbwy"/><stop offset="1" class="c3bch-exu"/><stop offset="1" class="o4i9h6buw"/></linearGradient><linearGradient id="ioqP4Zb" x1="14.008" x2="14.008" y1="30.293" y2="28.324" gradientUnits="userSpaceOnUse"><stop class="e-2abd5ql"/><stop offset="1" class="d7hfbsbga"/></linearGradient><linearGradient id="iAUq5QC" x1="14.648" x2="9.383" y1="28.824" y2="25.464" gradientUnits="userSpaceOnUse"><stop class="dq2vqeb7n"/><stop offset="1" class="ao7x5xbuq"/></linearGradient><linearGradient id="iv3kHxb" x1="17.844" x2="25.019" y1="29.88" y2="25.101" gradientUnits="userSpaceOnUse"><stop class="gdhzxbc-m"/><stop offset="1" class="ol8o05bqz"/></linearGradient><linearGradient id="iyDTxfd" x1="19.281" x2="19.281" y1="30.219" y2="28.813" gradientUnits="userSpaceOnUse"><stop class="h26o556mt"/><stop offset="1" class="oy7h34bgk"/></linearGradient><linearGradient id="iKQ1Fzb" x1="22.75" x2="18.842" y1="25.339" y2="28.573" gradientUnits="userSpaceOnUse"><stop class="norg35btb"/><stop offset="1" class="n-xdwifnc"/></linearGradient><linearGradient id="iZqvEvc" x1="19.813" x2="15.563" y1="5.563" y2="23.375" gradientUnits="userSpaceOnUse"><stop class="lhl06-bha"/><stop offset="1" class="kop0w9qcz"/></linearGradient><linearGradient id="i1HeMPc" x1="16" x2="16" y1="16.25" y2="19.625" gradientUnits="userSpaceOnUse"><stop class="o5v9tsbks"/><stop offset="1" class="ho539fzoe"/></linearGradient><linearGradient id="ijOHbmc" x1="14.648" x2="9.852" y1="27.192" y2="24.442" gradientUnits="userSpaceOnUse"><stop class="awtm28vjm"/><stop offset="1" class="q6d83lbcd"/></linearGradient><radialGradient id="imxBFlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.625 -.46875 0 16.313 27.031)" gradientUnits="userSpaceOnUse"><stop class="g_o8fz06n"/><stop offset="1" class="ju50frbjv"/></radialGradient><radialGradient id="ikOTO6d" cx="0" cy="0" r="1" gradientTransform="rotate(158.54 4.035 13.81)scale(4.86879 6.63165)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="wo8bwxbie"/><stop offset="1" class="emp987nse"/></radialGradient><radialGradient id="itYyQxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79687 .82813 -.17558 -.16895 24 25.016)" gradientUnits="userSpaceOnUse"><stop class="w3qgp_15u"/><stop offset="1" class="y7zl7wbxw"/></radialGradient><radialGradient id="i4VjeKy" cx="0" cy="0" r="1" gradientTransform="matrix(-7.75002 4.09373 -3.59354 -6.80308 21.438 11.906)" gradientUnits="userSpaceOnUse"><stop class="w038_rbmo"/><stop offset="1" class="x8cntjb9o"/></radialGradient><radialGradient id="ijA0fKe" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 8.459 8.907)scale(6.08437)" gradientUnits="userSpaceOnUse"><stop class="powb9hb_w"/><stop offset="1" class="ga84til7f"/></radialGradient><filter id="i0AnDrb" width="7.218" height="5.43" x="8.181" y="24.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7424" stdDeviation=".375"/></filter><filter id="itzXEDd" width="6.997" height="4.988" x="17.15" y="24.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7424" stdDeviation=".3"/></filter><filter id="isfy28d" width="21.911" height="22.258" x="5.045" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.775 0 0 0 0 0.571832 0 0 0 0 0.287396 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7424"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_7424" result="effect2_innerShadow_28327_7424"/></filter><filter id="iD8djKb" width="4.727" height="5.051" x="10.672" y="24.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7424" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sunflower" /></template>
<style>
.ac612il1b {
  d: path("M8.086 25.52c0 2.4 1.95 4.35 4.26 4.37l2.88.01c.14 0 .26-.12.25-.27c-.14-2.66-2.34-4.81-5.04-4.81h-2.07a.28.28 0 0 0-.28.28z");
}

.ao7x5xbuq {
  stop-color: var(--svg-color--619a6a, #619A6A);
}

.awtm28vjm {
  stop-color: var(--svg-color--86ad7a, #86AD7A);
}

.c3bch-exu {
  stop-color: var(--svg-color--008461, #008461);
}

.d7hfbsbga {
  stop-color: var(--svg-color--6f7e82, #6F7E82);
  stop-opacity: 0;
}

.dq2vqeb7n {
  stop-color: var(--svg-color--6fa06a, #6FA06A);
}

.e-2abd5ql {
  stop-color: var(--svg-color--6f7e82, #6F7E82);
}

.emp987nse {
  stop-color: var(--svg-color--92b196, #92B196);
}

.f_53usb0i {
  d: path("M26.947 14.45c.13-1.07-1.19-2.14-3.1-2.67c1.63-1.11 2.52-2.55 2.05-3.51c-.47-.97-2.16-1.15-4.05-.55c.76-1.82.73-3.51-.19-4.06c-.84-.51-2.18.08-3.37 1.35c-.33-1.7-1.15-2.9-2.13-2.91c-1.06-.03-1.97 1.33-2.31 3.22c-1.26-1.45-2.75-2.16-3.64-1.6c-.93.58-.92 2.34-.09 4.19c-1.94-.62-3.68-.42-4.15.58c-.45.97.47 2.4 2.13 3.49c-1.89.56-3.19 1.64-3.04 2.71s1.7 1.76 3.69 1.78c-1.28 1.5-1.78 3.11-1.07 3.93s2.39.55 4.06-.52c-.26 1.95.21 3.58 1.24 3.88c1.04.3 2.3-.84 3.12-2.65c.85 1.78 2.12 2.89 3.15 2.58s1.48-1.96 1.18-3.92c1.68 1.03 3.35 1.27 4.04.45c.7-.83.17-2.45-1.15-3.93c1.97-.06 3.5-.77 3.63-1.84m-10.49-3.03q.135.18.33.3c.16.09.33.14.52.16c.01.18.04.35.12.5c.08.16.2.3.35.42c-.09.15-.15.31-.17.49s.01.36.06.54c-.16.08-.3.18-.41.31c-.12.14-.19.31-.24.49c-.18-.02-.35-.01-.51.04c-.17.05-.33.15-.47.28c-.14-.11-.29-.2-.45-.25c-.18-.05-.36-.05-.54-.02a1.1 1.1 0 0 0-.25-.45a1.3 1.3 0 0 0-.44-.32c.05-.17.06-.34.04-.51c-.03-.18-.1-.35-.2-.51c.13-.12.24-.25.31-.41c.08-.18.11-.38.1-.59c.21-.02.41-.06.58-.17c.13-.08.24-.19.33-.31c.15.06.3.1.46.1q.255 0 .48-.09");
}

.ft5dv1b6b {
  fill: none;
}

.g_o8fz06n {
  stop-color: var(--svg-color--83b15d, #83B15D);
}

.g2e_9kb9s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.422 25.547c1.156.156 3.039 1.514 3.226 3.551");
}

.ga84til7f {
  stop-color: var(--svg-color--693542, #693542);
}

.gbpj3_blb {
  fill: var(--svg-color--63332a, #63332A);
  fill-rule: evenodd;
  d: path("m21.118 10.281l-.8.8l1.117 1.117l.295-.295a5.9 5.9 0 0 1 .071 2.076l-.366-.366l-1.114 1.114l.96.958a5.9 5.9 0 0 1-2.462 2.594l-1.027-1.023l-1.106 1.106l.515.515a5.9 5.9 0 0 1-2.437-.008l.508-.507l-1.117-1.117l-1.013 1.012a5.9 5.9 0 0 1-1.916-1.717l1.11 1.11l1.112-1.112l-1.112-1.112l-1.112 1.112a6 6 0 0 1-.523-.891l.928-.928l-1.112-1.112l-.325.325a5.9 5.9 0 0 1 .07-1.994l.255.255l1.096-1.095l-.762-.76q.245-.45.564-.85l.905.902l1.12-1.12l-.88-.877a6 6 0 0 1 .885-.53l.702.7l1.12-1.12l-.107-.105a6 6 0 0 1 1.633-.007l-.113.113l1.112 1.112l.716-.716q.47.224.89.523l-.899.9l1.112 1.111l.935-.935q.322.395.572.842m-.392 6.264l-1.113 1.113l-1.114-1.11l1.114-1.114zM11.224 12.9l1.112 1.112l1.098-1.099l-1.113-1.11zm1.804-1.804l1.114 1.11l1.118-1.118l-1.112-1.111zm1.827-1.826l1.112 1.11l1.118-1.117l-1.112-1.112zm1.82 1.817l1.117-1.117l1.112 1.111l-1.116 1.117zm-1.825 1.825l1.118-1.118l1.112 1.111l-1.116 1.117zm-1.807 1.807l1.1-1.1l1.114 1.11l-1.102 1.102zm7.685-1.814L19.61 11.79l-1.116 1.115l1.118 1.116zm-1.822 1.822l-1.118-1.116l-1.116 1.117l1.119 1.115zm-1.822 1.823l-1.12-1.115l-1.102 1.103l1.117 1.117z");
}

.gdhzxbc-m {
  stop-color: var(--svg-color--528c39, #528C39);
}

.h26o556mt {
  stop-color: var(--svg-color--6a806e, #6A806E);
}

.hinb-sbwy {
  stop-color: var(--svg-color--629b53, #629B53);
}

.hkr_8nbou {
  d: path("M16.79 29.18c0-2.4 1.95-4.35 4.26-4.37l2.88-.01c.14 0 .26.12.25.27c-.14 2.66-2.34 4.81-5.04 4.81h-2.07a.28.28 0 0 1-.28-.28z");
}

.ho539fzoe {
  stop-color: var(--svg-color--723152, #723152);
}

.jqamszbes {
  fill-rule: evenodd;
  d: path("m13.55 7.813l.666.666l.971-.971l-.15-.151a5.9 5.9 0 0 1 2.107.033l-.118.118l.971.971l.597-.597q.602.298 1.118.721l-.796.796l.956.955l.78-.78q.41.531.69 1.15l-.55.55l.986.987l.015-.015a5.9 5.9 0 0 1-.01 1.857l-.005-.004l-.971.971l.519.52a6 6 0 0 1-.695 1.142l-.743-.742l-.956.955l.752.753q-.517.419-1.123.715l-.548-.548l-.987.987l.05.05a5.9 5.9 0 0 1-1.97.03l.081-.08l-.987-.987l-.616.616a6 6 0 0 1-1.15-.69l.847-.846l-.956-.955l-.861.86a6 6 0 0 1-.721-1.117l.663-.663l-.971-.971l-.184.184a5.9 5.9 0 0 1-.013-2.22l.197.197l.987-.986l-.696-.696q.296-.605.715-1.123l.9.9l.956-.957l-.89-.89a6 6 0 0 1 1.143-.695m3.543 9.132l-.986.987l-.987-.987l.987-.987zm1.875-1.875l-.955.956l-.987-.987l.956-.956zm1.891-1.89l-.971.971l-.987-.987l.971-.971zM14.2 16.026l.987-.987l-.955-.956l-.987.987zm-1.875-1.875l.987-.987l-.971-.971l-.987.987zm4.737-.987l-.956.956l-.955-.956l.956-.956zm1.89-1.89l-.97.97l-.956-.955l.971-.971zm-4.72.97l.955-.955l-.971-.971l-.956.956zM17.078 9.4l-.971.97l-.972-.97l.972-.972z");
}

.ju50frbjv {
  stop-color: var(--svg-color--83b15d, #83B15D);
  stop-opacity: 0;
}

.k5za1xbln {
  d: path("M16 19a5.861 5.861 0 1 0 0-11.722A5.861 5.861 0 0 0 16 19");
}

.kop0w9qcz {
  stop-color: var(--svg-color--f7b44b, #F7B44B);
}

.l9miucc0b {
  stop-color: var(--svg-color--5da112, #5DA112);
}

.lcl8i2bvp {
  stop-color: var(--svg-color--8fb87f, #8FB87F);
}

.lhl06-bha {
  stop-color: var(--svg-color--ffe447, #FFE447);
}

.lr_grnbee {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
}

.n-xdwifnc {
  stop-color: var(--svg-color--7ba561, #7BA561);
}

.n4t4mlb3d {
  stop-color: var(--svg-color--8fb87f, #8FB87F);
  stop-opacity: 0;
}

.norg35btb {
  stop-color: var(--svg-color--87be58, #87BE58);
}

.o4i9h6buw {
  stop-color: var(--svg-color--4d9055, #4D9055);
}

.o5v9tsbks {
  stop-color: var(--svg-color--723152, #723152);
  stop-opacity: 0;
}

.ol8o05bqz {
  stop-color: var(--svg-color--81bd52, #81BD52);
}

.oy7h34bgk {
  stop-color: var(--svg-color--6a806e, #6A806E);
  stop-opacity: 0;
}

.powb9hb_w {
  stop-color: var(--svg-color--8c6161, #8C6161);
}

.q6d83lbcd {
  stop-color: var(--svg-color--86ad7a, #86AD7A);
  stop-opacity: 0;
}

.rv1nhib-j {
  d: path("M17.107 19.75h-2v10.13h2z");
}

.sddv6hldr {
  stop-color: var(--svg-color--74a93f, #74A93F);
}

.tju132bmi {
  stop-color: var(--svg-color--8ed800, #8ED800);
}

.u_9wfp45e {
  d: path("M16.947 29.2c0-2.4 1.95-4.35 4.26-4.37l2.88-.01c.14 0 .26.12.25.27c-.14 2.66-2.34 4.81-5.04 4.81h-2.07a.28.28 0 0 1-.28-.28z");
}

.u-1se5bme {
  stop-color: var(--svg-color--9c634d, #9C634D);
}

.v-bq8jb7v {
  stop-color: var(--svg-color--f7be1e, #F7BE1E);
}

.v8r_yhmkz {
  d: path("M17.75 28.606c0-1.79 1.53-3.244 3.341-3.26l2.26-.007c.11 0 .203.09.195.202c-.11 1.983-1.835 3.587-3.953 3.587H17.97a.214.214 0 0 1-.22-.21z");
}

.w038_rbmo {
  stop-color: var(--svg-color--966261, #966261);
}

.w3qgp_15u {
  stop-color: var(--svg-color--9dd271, #9DD271);
}

.w9pzy0b1z {
  d: path("M8.93 25.917c0 1.856 1.51 3.365 3.297 3.38l2.228.008a.195.195 0 0 0 .193-.209c-.108-2.057-1.81-3.72-3.9-3.72h-1.6c-.124 0-.217.1-.217.216z");
}

.wnjx4wbjd {
  stop-color: var(--svg-color--51923c, #51923C);
  stop-opacity: 0;
}

.wo8bwxbie {
  stop-color: var(--svg-color--92b196, #92B196);
  stop-opacity: 0;
}

.x8cntjb9o {
  stop-color: var(--svg-color--7b454a, #7B454A);
}

.xpg7qbdiy {
  stop-color: var(--svg-color--63332a, #63332A);
}

.y7zl7wbxw {
  stop-color: var(--svg-color--9dd271, #9DD271);
  stop-opacity: 0;
}

.y8f693b9e {
  stop-color: var(--svg-color--51923c, #51923C);
}

.yj416jhwz {
  d: path("M8.094 25.5c0 2.4 1.95 4.35 4.26 4.37l2.88.01c.14 0 .26-.12.25-.27c-.14-2.66-2.34-4.81-5.04-4.81h-2.07a.28.28 0 0 0-.28.28z");
}

</style>
