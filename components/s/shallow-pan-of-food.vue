<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ec8xgab-d"/><path fill="url(#icvuMwn)" clip-rule="evenodd" class="cu8dzoq1k"/><g filter="url(#iHqYYIb)"><path stroke="url(#iCwmNtb)" class="p51-vsb1a"/></g><path clip-rule="evenodd" class="rsknmrbna"/><g filter="url(#itYca6d)"><path stroke="url(#iom7Oye)" class="o0-1v7b4n"/></g><circle fill="url(#izqfCyb)" class="kyyda5aut"/><g filter="url(#i3xeFwd)"><circle fill="url(#iIcylVE)" class="og1z2sboq"/><circle fill="url(#iAbulwe)" class="og1z2sboq"/></g><circle fill="url(#i3fl4CN)" class="o7qtmib6t"/><circle fill="url(#ilPibLu)" class="o7qtmib6t"/><g filter="url(#iLokIId)"><path class="d2u4tacck"/></g><path fill="url(#igsK3He)" class="bm57x4c5s"/><g filter="url(#irlrPrd)"><path fill="url(#icYjVrd)" class="t6lfsq8tg"/></g><g filter="url(#iZanM2d)"><path class="qzn8vnb2i"/></g><g filter="url(#ixFPX1C)"><path class="ja28v8b4h"/></g><g filter="url(#iIAzrad)"><path class="rx2dhrqts"/></g><path class="u9hc_9qvb"/><path fill="url(#iyDvize)" class="agcr--r6k"/><path class="fxa49fbaj"/><path fill="url(#iWyszBd)" class="gqwxlrlxt"/><path class="jdr9kf3pp"/><path fill="url(#iJ0al6x)" class="tfjyb3lub"/><g filter="url(#iFXjhMc)"><path class="ql_prbbos"/></g><path fill="url(#iMJR00c)" class="bj-hj0zgy"/><path fill="url(#ivW0Kdd)" class="bj-hj0zgy"/><g filter="url(#i5eGFke)"><path fill="url(#ihFuUZc)" class="p_0mz3bdp"/></g><g filter="url(#iAmOVhc)"><path fill="url(#i6XbT8b)" class="r9m6-3r4d"/></g><g filter="url(#iHuTTie)"><path class="lh2a_2bvg"/></g><path fill="url(#iy7PRDe)" class="pi4tekqap"/><path fill="url(#ikD6bPd)" class="pi4tekqap"/><path fill="url(#iIH2hMc)" class="pi4tekqap"/><g filter="url(#iHXS5dd)"><path stroke="url(#ime5jGx)" class="x-349kyds"/></g><g filter="url(#is4EWDd)"><path class="xvidy-bte"/></g><path fill="url(#izDuG9z)" class="ef57u3bfw"/><path fill="url(#iLkbf6c)" class="ef57u3bfw"/><g filter="url(#i16Ppbb)"><path stroke="url(#i3iECRJ)" class="ttfrw_bbo"/></g><g filter="url(#iSYYUSd)"><path stroke="url(#iKX0Vcd)" class="tcuberb-j"/></g><g filter="url(#iBrgHde)"><path stroke="url(#igMwp1b)" class="o3622qb5b"/></g><g filter="url(#il2m5FK)"><path fill="url(#iZrpoze)" class="ydv4-sb5p"/></g><g filter="url(#isPEaob)"><path fill="url(#ior20yb)" class="u7ufwxaae"/></g><g filter="url(#iAjc5pd)"><path fill="url(#ipGzL4d)" class="o8i0_9buw"/></g><g filter="url(#i21ECQd)"><path stroke="url(#iJZsjKa)" class="qq-i73bai"/></g><defs><filter id="iHqYYIb" width="6.256" height="5.752" x="4.286" y="4.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="itYca6d" width="6.282" height="6.187" x="21.207" y="21.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="i3xeFwd" width="22.901" height="22.901" x="4.599" y="4.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".25"/></filter><filter id="iLokIId" width="15.898" height="15.527" x="7.659" y="7.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".25"/></filter><filter id="irlrPrd" width="14.591" height="14.24" x="8.716" y="8.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iZanM2d" width="1.973" height="1.973" x="16.445" y="10.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="ixFPX1C" width="1.973" height="1.973" x="9.75" y="16.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iIAzrad" width="1.973" height="1.973" x="17.714" y="19.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iFXjhMc" width="2.206" height="4.378" x="17.817" y="13.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="i5eGFke" width="4.292" height="2.679" x="11.221" y="11.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iAmOVhc" width="5.037" height="2.862" x="10.497" y="11.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iHuTTie" width="4.334" height="2.442" x="11.206" y="11.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iHXS5dd" width="3.314" height="1.614" x="12.096" y="11.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="is4EWDd" width="3.665" height="3.683" x="12.588" y="17.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="i16Ppbb" width="1.063" height="3.438" x="18.906" y="14.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iSYYUSd" width="3.922" height="2.156" x="11.609" y="11.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".25"/></filter><filter id="iBrgHde" width="2.695" height="2.631" x="13.54" y="17.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="il2m5FK" width="1.381" height="1.806" x="11.466" y="12.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="isPEaob" width="1.545" height="1.609" x="12.903" y="17.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="iAjc5pd" width="1.882" height="1.193" x="18.085" y="16.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><filter id="i21ECQd" width="5.281" height="6.875" x="18.031" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33564" stdDeviation=".125"/></filter><linearGradient id="iCwmNtb" x1="4.661" x2="8.828" y1="8.875" y2="4.531" gradientUnits="userSpaceOnUse"><stop class="vn9xb7bac"/><stop offset=".277" class="ikxpt9bof"/><stop offset=".832" class="ifrbn0b7t"/><stop offset="1" class="p8br8gnfw"/></linearGradient><linearGradient id="iom7Oye" x1="27.088" x2="22.922" y1="23.002" y2="27.345" gradientUnits="userSpaceOnUse"><stop class="vn9xb7bac"/><stop offset=".277" class="ikxpt9bof"/><stop offset=".832" class="ifrbn0b7t"/><stop offset="1" class="p8br8gnfw"/></linearGradient><linearGradient id="izqfCyb" x1="24.807" x2="6.798" y1="8.748" y2="22.587" gradientUnits="userSpaceOnUse"><stop class="m-46u_1un"/><stop offset=".506" class="qhdxlkbzx"/><stop offset="1" class="gpwo9mbit"/></linearGradient><linearGradient id="iIcylVE" x1="25.147" x2="8.314" y1="8.672" y2="23.496" gradientUnits="userSpaceOnUse"><stop class="zwaomlh3y"/><stop offset=".449" class="qp4vm7b8r"/><stop offset="1" class="i569tjbyj"/></linearGradient><linearGradient id="igsK3He" x1="21.563" x2="10.375" y1="11.438" y2="19.125" gradientUnits="userSpaceOnUse"><stop class="jrxth4bfy"/><stop offset=".159" class="vglirobiy"/><stop offset=".642" class="dnzejcodg"/><stop offset="1" class="g48y6wbtu"/></linearGradient><linearGradient id="icYjVrd" x1="21.063" x2="10.75" y1="11.563" y2="19.813" gradientUnits="userSpaceOnUse"><stop class="d5_j5ft3l"/><stop offset=".517" class="ex4_2kakc"/><stop offset="1" class="bf-55ob4j"/></linearGradient><linearGradient id="iMJR00c" x1="19.563" x2="19.147" y1="14.003" y2="17.931" gradientUnits="userSpaceOnUse"><stop class="kfhyjmbqz"/><stop offset="1" class="t_hrfyb4t"/></linearGradient><linearGradient id="ihFuUZc" x1="16.07" x2="10.883" y1="11.801" y2="13.239" gradientUnits="userSpaceOnUse"><stop offset=".793" class="iws57vk2h"/><stop offset="1" class="d5n9e6bwk"/></linearGradient><linearGradient id="i6XbT8b" x1="16.094" x2="10.906" y1="11.844" y2="13.281" gradientUnits="userSpaceOnUse"><stop offset=".793" class="o2qpeg0du"/><stop offset="1" class="c82bisbfw"/></linearGradient><linearGradient id="iy7PRDe" x1="15.636" x2="11.829" y1="12.086" y2="13.361" gradientUnits="userSpaceOnUse"><stop class="kfhyjmbqz"/><stop offset="1" class="t_hrfyb4t"/></linearGradient><linearGradient id="ime5jGx" x1="14.968" x2="12.375" y1="11.903" y2="12.875" gradientUnits="userSpaceOnUse"><stop class="vi7a2zbgm"/><stop offset="1" class="zxqyxd9vk"/></linearGradient><linearGradient id="izDuG9z" x1="15.972" x2="13.158" y1="20.56" y2="17.697" gradientUnits="userSpaceOnUse"><stop class="kfhyjmbqz"/><stop offset="1" class="t_hrfyb4t"/></linearGradient><linearGradient id="i3iECRJ" x1="19.438" x2="19.438" y1="14.625" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="efyv-bcrg"/><stop offset="1" class="zxqyxd9vk"/></linearGradient><linearGradient id="iKX0Vcd" x1="14.852" x2="12.438" y1="11.896" y2="13.075" gradientUnits="userSpaceOnUse"><stop class="ii5ij5bxi"/><stop offset="1" class="tr-ey4z4j"/></linearGradient><linearGradient id="igMwp1b" x1="15.844" x2="14.25" y1="19.678" y2="18" gradientUnits="userSpaceOnUse"><stop class="efyv-bcrg"/><stop offset="1" class="zxqyxd9vk"/></linearGradient><linearGradient id="iZrpoze" x1="11.813" x2="12.598" y1="13.164" y2="12.962" gradientUnits="userSpaceOnUse"><stop class="p4i3r1tkv"/><stop offset="1" class="hl-hd9byo"/></linearGradient><linearGradient id="ior20yb" x1="13.297" x2="13.842" y1="17.672" y2="18.273" gradientUnits="userSpaceOnUse"><stop class="wwa9lpz_v"/><stop offset="1" class="hl-hd9byo"/></linearGradient><linearGradient id="ipGzL4d" x1="18.987" x2="19.127" y1="17.809" y2="17.01" gradientUnits="userSpaceOnUse"><stop class="wwa9lpz_v"/><stop offset="1" class="hl-hd9byo"/></linearGradient><linearGradient id="iJZsjKa" x1="18.406" x2="23.188" y1="9" y2="15.594" gradientUnits="userSpaceOnUse"><stop class="pne502b-x"/><stop offset=".187" class="izutjjo9i"/><stop offset=".455" class="ys_gktbuw"/><stop offset=".727" class="grblhmeft"/><stop offset="1" class="vvht-9bqy"/></linearGradient><radialGradient id="icvuMwn" cx="0" cy="0" r="1" gradientTransform="matrix(-3.17185 3.15627 -.77936 -.78321 8.297 8.281)" gradientUnits="userSpaceOnUse"><stop class="bt6v28bfx"/><stop offset=".439" class="ndry2fbqq"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iAbulwe" cx="0" cy="0" r="1" gradientTransform="rotate(82.447 -2.572 16.061)scale(17.9684)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="r3qjcopwk"/><stop offset=".431" class="mmohku0ok"/></radialGradient><radialGradient id="i3fl4CN" cx="0" cy="0" r="1" gradientTransform="rotate(-3.391 281.166 -179.894)scale(16.8117)" gradientUnits="userSpaceOnUse"><stop class="m96h-4brc"/><stop offset=".466" class="xkhxocchr"/><stop offset="1" class="vuad6pb7r"/></radialGradient><radialGradient id="ilPibLu" cx="0" cy="0" r="1" gradientTransform="rotate(111.224 5.712 13.334)scale(13.7359)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="a7c1lh7oq"/><stop offset="1" class="x-audowon"/></radialGradient><radialGradient id="iyDvize" cx="0" cy="0" r="1" gradientTransform="rotate(110.759 4.963 12.044)scale(.9192)" gradientUnits="userSpaceOnUse"><stop class="qr94dx2_n"/><stop offset=".472" class="e9faqib4t"/><stop offset="1" class="aiu2lpbzf"/></radialGradient><radialGradient id="iWyszBd" cx="0" cy="0" r="1" gradientTransform="rotate(110.759 2.765 16.56)scale(.9192)" gradientUnits="userSpaceOnUse"><stop class="qr94dx2_n"/><stop offset=".472" class="e9faqib4t"/><stop offset="1" class="aiu2lpbzf"/></radialGradient><radialGradient id="iJ0al6x" cx="0" cy="0" r="1" gradientTransform="rotate(110.759 -.224 12.351)scale(.9192)" gradientUnits="userSpaceOnUse"><stop class="qr94dx2_n"/><stop offset=".472" class="e9faqib4t"/><stop offset="1" class="aiu2lpbzf"/></radialGradient><radialGradient id="ivW0Kdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.19714 2.625 -1.08146 -.08122 19.344 17.5)" gradientUnits="userSpaceOnUse"><stop class="y9href2hi"/><stop offset="1" class="x_cra55-u"/></radialGradient><radialGradient id="ikD6bPd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46606 .7791 -.32098 -1.01598 12.331 12.738)" gradientUnits="userSpaceOnUse"><stop class="y9href2hi"/><stop offset="1" class="x_cra55-u"/></radialGradient><radialGradient id="iIH2hMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 .14062 -.12991 -.27426 15.094 12.055)" gradientUnits="userSpaceOnUse"><stop class="ivvf_w0ll"/><stop offset="1" class="lwv_izbai"/></radialGradient><radialGradient id="iLkbf6c" cx="0" cy="0" r="1" gradientTransform="rotate(-133.531 10.806 5.946)scale(2.58621 1.06548)" gradientUnits="userSpaceOnUse"><stop class="y9href2hi"/><stop offset="1" class="x_cra55-u"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shallow-pan-of-food" /></template>
<style>
.a7c1lh7oq {
  stop-color: var(--svg-color--5e3f77, #5E3F77);
  stop-opacity: 0;
}

.agcr--r6k {
  d: path("M17.138 12.316a.737.737 0 1 0 1.041-1.042a.737.737 0 0 0-1.041 1.042");
}

.aiu2lpbzf {
  stop-color: var(--svg-color--c6453d, #C6453D);
}

.bf-55ob4j {
  stop-color: var(--svg-color--ffde42, #FFDE42);
}

.bj-hj0zgy {
  d: path("M19.343 14.044a.665.665 0 0 1 .594.73l-.257 2.521a.665.665 0 1 1-1.324-.135l.257-2.522a.665.665 0 0 1 .73-.594");
}

.bm57x4c5s {
  d: path("M16.094 22.656c.764 0 1.532.445 2.234.227c.718-.234 1.126-1.134 1.735-1.57c.608-.437 1.461-.54 1.906-1.141c.55-.742.362-1.787.596-2.504c.226-.694.896-1.185.896-1.965c0-.764-.75-1.614-.977-2.308c-.234-.717.036-1.46-.414-2.09c-.514-.72-1.415-.806-2.023-1.242c-.593-.437-.886-1.257-1.758-1.541s-1.54.197-2.32.197c-.764 0-1.283-.514-2.254-.197c-.717.233-1.185 1.104-1.793 1.54c-.608.437-1.45.534-1.895 1.134c-.511.691-.277 1.555-.511 2.273c-.226.694-.953 1.447-.953 2.226c0 .764.646 1.392.872 2.086c.234.718 0 1.649.627 2.407c.437.608 1.252.625 1.86 1.062c.592.437 1.064 1.399 1.781 1.633c.71.226 1.627-.227 2.39-.227");
}

.bt6v28bfx {
  stop-color: var(--svg-color--3f3749, #3F3749);
}

.c82bisbfw {
  stop-color: var(--svg-color--d3ab3e, #D3AB3E);
  stop-opacity: 0;
}

.cu8dzoq1k {
  fill-rule: evenodd;
  d: path("M8.391 5.423c-.241-.032-.455.025-.616.172c-.642.59-1.39 1.348-1.946 1.912l-.444.448c-.374.374-.377.654-.33.84c.057.232.228.434.35.544l.006.005l1.533 1.468a.5.5 0 1 1-.691.722L4.73 10.077c-.191-.174-.52-.537-.646-1.04c-.139-.556-.005-1.19.594-1.789l.424-.429A60 60 0 0 1 7.1 4.859c.419-.386.946-.49 1.42-.428c.465.06.912.281 1.23.597c.237.235.511.5.777.755l.043.041c.25.24.49.472.679.659a.5.5 0 0 1-.704.71c-.183-.181-.42-.408-.672-.651l-.039-.038a77 77 0 0 1-.788-.766a1.18 1.18 0 0 0-.655-.315");
}

.d2u4tacck {
  fill: var(--svg-color--393138, #393138);
  d: path("M15.69 22.656c.764 0 1.532.445 2.234.227c.718-.234 1.126-1.134 1.735-1.57c.608-.437 1.461-.54 1.906-1.141c.55-.742.362-1.787.596-2.504c.226-.694.896-1.185.896-1.965c0-.764-.75-1.614-.977-2.308c-.233-.717.036-1.46-.414-2.09c-.514-.72-1.415-.806-2.023-1.242c-.593-.437-.886-1.257-1.758-1.541s-1.54.197-2.32.197c-.764 0-1.283-.514-2.254-.197c-.717.233-1.185 1.104-1.793 1.54c-.608.437-1.45.534-1.895 1.134c-.511.691-.277 1.555-.511 2.273c-.226.694-.953 1.447-.953 2.226c0 .764.646 1.392.872 2.086c.234.718 0 1.649.628 2.407c.436.608 1.25.625 1.859 1.062c.592.437 1.064 1.399 1.781 1.633c.71.226 1.627-.227 2.39-.227");
}

.d5_j5ft3l {
  stop-color: var(--svg-color--f9b93f, #F9B93F);
}

.d5n9e6bwk {
  stop-color: var(--svg-color--9e7830, #9E7830);
  stop-opacity: 0;
}

.dnzejcodg {
  stop-color: var(--svg-color--f4c52e, #F4C52E);
}

.e9faqib4t {
  stop-color: var(--svg-color--ff4e3c, #FF4E3C);
}

.ec8xgab-d {
  fill: var(--svg-color--5f4982, #5F4982);
  fill-rule: evenodd;
  d: path("M8.391 5.423c-.241-.032-.455.025-.616.172c-.642.59-1.39 1.348-1.946 1.912l-.444.448c-.374.374-.377.654-.33.84c.057.232.228.434.35.544l.006.005l1.533 1.468a.5.5 0 1 1-.691.722L4.73 10.077c-.191-.174-.52-.537-.646-1.04c-.139-.556-.005-1.19.594-1.789l.424-.429A60 60 0 0 1 7.1 4.859c.419-.386.946-.49 1.42-.428c.465.06.912.281 1.23.597c.237.235.511.5.777.755l.043.041c.25.24.49.472.679.659a.5.5 0 0 1-.704.71c-.183-.181-.42-.408-.672-.651l-.039-.038a77 77 0 0 1-.788-.766a1.18 1.18 0 0 0-.655-.315");
}

.ef57u3bfw {
  d: path("M16.081 20.361a.676.676 0 0 1-.956-.005l-1.812-1.83a.676.676 0 0 1 .96-.952l1.813 1.83a.676.676 0 0 1-.005.957");
}

.efyv-bcrg {
  stop-color: var(--svg-color--89d18e, #89D18E);
}

.ex4_2kakc {
  stop-color: var(--svg-color--ffd941, #FFD941);
}

.ft5dv1b6b {
  fill: none;
}

.fxa49fbaj {
  fill: var(--svg-color--c9433e, #C9433E);
  d: path("M18.384 20.488a.737.737 0 1 0 1.042-1.042a.737.737 0 0 0-1.042 1.041");
}

.g48y6wbtu {
  stop-color: var(--svg-color--e4c03c, #E4C03C);
}

.gpwo9mbit {
  stop-color: var(--svg-color--4d3966, #4D3966);
}

.gqwxlrlxt {
  d: path("M18.384 20.488a.737.737 0 1 0 1.042-1.042a.737.737 0 0 0-1.042 1.041");
}

.grblhmeft {
  stop-color: var(--svg-color--ffd07c, #FFD07C);
}

.hl-hd9byo {
  stop-color: var(--svg-color--6b9134, #6B9134);
  stop-opacity: 0;
}

.i569tjbyj {
  stop-color: var(--svg-color--5d3f7c, #5D3F7C);
}

.ifrbn0b7t {
  stop-color: var(--svg-color--654d8d, #654D8D);
}

.ii5ij5bxi {
  stop-color: var(--svg-color--67b35b, #67B35B);
}

.ikxpt9bof {
  stop-color: var(--svg-color--7456a6, #7456A6);
}

.ivvf_w0ll {
  stop-color: var(--svg-color--8ad291, #8AD291);
}

.iws57vk2h {
  stop-color: var(--svg-color--9e7830, #9E7830);
}

.izutjjo9i {
  stop-color: var(--svg-color--ffd874, #FFD874);
}

.ja28v8b4h {
  fill: var(--svg-color--b36d31, #B36D31);
  d: path("M10.216 17.667a.737.737 0 1 0 1.042-1.042a.737.737 0 0 0-1.042 1.042");
}

.jdr9kf3pp {
  fill: var(--svg-color--c9433e, #C9433E);
  d: path("M10.4 17.581a.737.737 0 1 0 1.041-1.041a.737.737 0 0 0-1.041 1.041");
}

.jrxth4bfy {
  stop-color: var(--svg-color--c6943b, #C6943B);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.kfhyjmbqz {
  stop-color: var(--svg-color--539253, #539253);
}

.kyyda5aut {
  cx: 16.049px;
  cy: 15.763px;
  r: 11.487px;
}

.lh2a_2bvg {
  fill: var(--svg-color--a27932, #A27932);
  d: path("M15.25 11.978c.12.354-.043.599-.396.719l-2.44.826c-.354.12-.81.104-.93-.25c-.12-.353.16-.615.514-.735l2.44-.827c.353-.12.693-.086.813.267");
}

.lwv_izbai {
  stop-color: var(--svg-color--88cf90, #88CF90);
  stop-opacity: 0;
}

.m-46u_1un {
  stop-color: var(--svg-color--7e75bf, #7E75BF);
}

.m96h-4brc {
  stop-color: var(--svg-color--654b7e, #654B7E);
}

.mmohku0ok {
  stop-color: var(--svg-color--7e6898, #7E6898);
  stop-opacity: 0;
}

.ndry2fbqq {
  stop-color: var(--svg-color--332d3b, #332D3B);
}

.o0-1v7b4n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M25.797 21.594s.304.267.93.9c.624.632.378 1.267.062 1.648c-.344.414-1.753 1.755-2.555 2.547a1.335 1.335 0 0 1-1.781 0c-.434-.363-.663-.61-.871-.809");
}

.o2qpeg0du {
  stop-color: var(--svg-color--d5ab3e, #D5AB3E);
}

.o3622qb5b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.915 17.797l1.945 1.881");
}

.o7qtmib6t {
  cx: 16.049px;
  cy: 15.763px;
  r: 8.951px;
}

.o8i0_9buw {
  d: path("M18.915 17.867c-.328-.035-.58-.692-.58-.692c.75.747 1.382.102 1.382.102c-.025.163-.473.624-.802.59");
}

.og1z2sboq {
  cx: 16.049px;
  cy: 15.763px;
  r: 10.95px;
}

.p_0mz3bdp {
  d: path("M15.227 12.018a.676.676 0 0 1-.423.857l-2.44.827a.676.676 0 1 1-.434-1.28l2.44-.827c.354-.12.737.07.857.423");
}

.p4i3r1tkv {
  stop-color: var(--svg-color--6b9134, #6B9134);
}

.p51-vsb1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.5 9.86s.148.156-.477-.477s-.316-1.182 0-1.563c.344-.414 1.753-1.755 2.555-2.547c.248-.244.97-.713 1.719-.085c.433.363.663.61.87.808");
}

.p8br8gnfw {
  stop-color: var(--svg-color--7b69a3, #7B69A3);
}

.pi4tekqap {
  d: path("M15.505 11.901a.676.676 0 0 1-.423.857l-2.44.827a.676.676 0 1 1-.434-1.28l2.44-.827c.354-.12.737.07.857.423");
}

.pne502b-x {
  stop-color: var(--svg-color--f8c05b, #F8C05B);
  stop-opacity: 0;
}

.qhdxlkbzx {
  stop-color: var(--svg-color--58457c, #58457C);
}

.ql_prbbos {
  fill: var(--svg-color--9d7b30, #9D7B30);
  d: path("M19.175 14.146a.666.666 0 0 1 .594.73l-.257 2.52c-.038.366-.482.658-.847.62a.665.665 0 0 1-.594-.729l.257-2.521c.038-.366.481-.658.847-.62");
}

.qp4vm7b8r {
  stop-color: var(--svg-color--5c4385, #5C4385);
}

.qq-i73bai {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.406 9c.547.25.672.89 1.266 1.344c.58.442 1.452.538 1.875 1.062c.328.406.484.83.484 2.188c0 .61.547 1.125.907 1.531");
}

.qr94dx2_n {
  stop-color: var(--svg-color--ff8981, #FF8981);
}

.qzn8vnb2i {
  fill: var(--svg-color--b36d31, #B36D31);
  d: path("M16.91 12.433a.737.737 0 1 0 1.042-1.042a.737.737 0 0 0-1.042 1.042");
}

.r3qjcopwk {
  stop-color: var(--svg-color--b5a4cb, #B5A4CB);
}

.r9m6-3r4d {
  d: path("M15.25 12.06c.12.354-.092.691-.446.811l-3.187 1.05c-.354.12-.714-.022-.834-.376a.676.676 0 0 1 .424-.857l3.186-1.05a.676.676 0 0 1 .858.422");
}

.rsknmrbna {
  fill: var(--svg-color--513d75, #513D75);
  fill-rule: evenodd;
  d: path("m25.701 24.694l.445-.448c.373-.374.376-.654.33-.84c-.058-.232-.229-.434-.35-.544l-.007-.005l-1.533-1.468a.5.5 0 0 1 .692-.723l1.522 1.458c.192.174.521.537.646 1.04c.14.556.006 1.19-.593 1.789c-.117.117-.262.263-.425.429a60 60 0 0 1-1.997 1.96c-.42.385-.947.49-1.42.428a2.17 2.17 0 0 1-1.23-.597c-.238-.235-.512-.5-.778-.756l-.042-.04c-.25-.24-.491-.472-.68-.66a.5.5 0 0 1 .705-.71c.183.182.419.41.67.652l.04.038c.266.255.545.524.788.766c.162.16.406.283.655.315c.242.031.455-.025.616-.172a58 58 0 0 0 1.946-1.912");
}

.rx2dhrqts {
  fill: var(--svg-color--b36d31, #B36D31);
  d: path("M18.18 20.61a.737.737 0 1 0 1.042-1.042a.737.737 0 0 0-1.042 1.042");
}

.t_hrfyb4t {
  stop-color: var(--svg-color--72ab42, #72AB42);
}

.t6lfsq8tg {
  d: path("M16.09 22.278c.722 0 1.449.42 2.113.214c.678-.22 1.065-1.072 1.64-1.485s1.382-.51 1.803-1.079c.52-.702.343-1.69.564-2.368c.214-.656.847-1.12.847-1.858c0-.723-.71-1.527-.924-2.183c-.22-.678.034-1.381-.391-1.977c-.486-.68-1.339-.762-1.914-1.175c-.56-.413-.838-1.188-1.662-1.457c-.825-.269-1.457.186-2.195.186c-.723 0-1.213-.485-2.131-.186c-.678.221-1.121 1.044-1.696 1.457s-1.372.504-1.792 1.072c-.484.654-.263 1.471-.484 2.15c-.214.656-.902 1.368-.902 2.106c0 .722.612 1.316.825 1.972c.222.679 0 1.56.594 2.276c.413.575 1.184.592 1.759 1.005c.56.413 1.006 1.323 1.684 1.544c.671.214 1.539-.214 2.261-.214");
}

.tcuberb-j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m14.906 12.063l-2.672.906");
}

.tfjyb3lub {
  d: path("M10.4 17.581a.737.737 0 1 0 1.041-1.041a.737.737 0 0 0-1.041 1.041");
}

.tr-ey4z4j {
  stop-color: var(--svg-color--7ccd45, #7CCD45);
}

.ttfrw_bbo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.594 14.625l-.313 2.688");
}

.u7ufwxaae {
  d: path("M13.296 17.58c.229-.237.902-.033.902-.033c-1.05.133-.93 1.027-.93 1.027c-.112-.119-.2-.756.028-.994");
}

.u9hc_9qvb {
  fill: var(--svg-color--c9433e, #C9433E);
  d: path("M17.138 12.316a.737.737 0 1 0 1.041-1.042a.737.737 0 0 0-1.041 1.042");
}

.vglirobiy {
  stop-color: var(--svg-color--dfa930, #DFA930);
}

.vi7a2zbgm {
  stop-color: var(--svg-color--74ad78, #74AD78);
}

.vn9xb7bac {
  stop-color: var(--svg-color--7a69a3, #7A69A3);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vvht-9bqy {
  stop-color: var(--svg-color--f5bf5f, #F5BF5F);
  stop-opacity: 0;
}

.wwa9lpz_v {
  stop-color: var(--svg-color--79a53b, #79A53B);
}

.x_cra55-u {
  stop-color: var(--svg-color--96e839, #96E839);
  stop-opacity: 0;
}

.x-349kyds {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m15.035 12.045l-2.564.864");
}

.x-audowon {
  stop-color: var(--svg-color--60407c, #60407C);
}

.xkhxocchr {
  stop-color: var(--svg-color--4d3a5e, #4D3A5E);
}

.xvidy-bte {
  fill: var(--svg-color--a07a34, #A07A34);
  d: path("M15.802 20.536a.676.676 0 0 1-.956-.005l-1.813-1.83a.676.676 0 0 1 .961-.952l1.813 1.83a.676.676 0 0 1-.005.957");
}

.y9href2hi {
  stop-color: var(--svg-color--90e43c, #90E43C);
}

.ydv4-sb5p {
  d: path("M11.73 13.122c-.104-.313.391-.813.391-.813c-.094.75.477 1.3.477 1.3c-.158.044-.763-.174-.867-.487");
}

.ys_gktbuw {
  stop-color: var(--svg-color--e7b052, #E7B052);
}

.zwaomlh3y {
  stop-color: var(--svg-color--5e50a1, #5E50A1);
}

.zxqyxd9vk {
  stop-color: var(--svg-color--b9f270, #B9F270);
}

</style>
