<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijCzg5B)"><path fill="url(#iy3PMQd)" class="s2al21b8l"/></g><g filter="url(#iYoDFud)"><path fill="url(#ipje2Kp)" class="reu5_10ar"/></g><g filter="url(#inoxtic)"><path fill="url(#iMddiab)" class="syuxsmbeu"/></g><g filter="url(#ituDD8d)"><path fill="url(#i1HgCtd)" class="omyjt1b7q"/></g><g filter="url(#iJ6ocpW)"><path class="f_u2nyu6r"/></g><defs><filter id="ijCzg5B" width="5.484" height="6.45" x="1.76" y="23.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.470588 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.361875 0 0 0 0 0.804167 0 0 0 0 0.607593 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4874" result="effect2_innerShadow_18_4874"/></filter><filter id="iYoDFud" width="5.4" height="3.3" x="7.81" y="24.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.458824 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.537255 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4874" result="effect2_innerShadow_18_4874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.764706 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_4874" result="effect3_innerShadow_18_4874"/></filter><filter id="inoxtic" width="19.962" height="16.249" x="6.218" y="10.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 1 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.454902 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4874" result="effect2_innerShadow_18_4874"/></filter><filter id="ituDD8d" width="9.5" height="7.51" x="20.75" y="1.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.541176 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 1 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4874" result="effect2_innerShadow_18_4874"/></filter><filter id="iJ6ocpW" width="2.21" height="2.21" x="18.91" y="13.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180191 0 0 0 0 0.445833 0 0 0 0 0.389712 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4874"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.811765 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4874" result="effect2_innerShadow_18_4874"/></filter><linearGradient id="iy3PMQd" x1="2.635" x2="7.385" y1="27.563" y2="27.563" gradientUnits="userSpaceOnUse"><stop class="p65z65b6q"/><stop offset="1" class="d5gxk6bzj"/></linearGradient><linearGradient id="ipje2Kp" x1="8.01" x2="13.01" y1="27.697" y2="25.01" gradientUnits="userSpaceOnUse"><stop class="o6vkxo51a"/><stop offset="1" class="k4qlbz9tl"/></linearGradient><linearGradient id="i1HgCtd" x1="21.635" x2="27.635" y1="9" y2="2.437" gradientUnits="userSpaceOnUse"><stop class="hu3k27bzb"/><stop offset="1" class="zqi7brybz"/></linearGradient><radialGradient id="iMddiab" cx="0" cy="0" r="1" gradientTransform="matrix(-8.43748 10.25006 -8.2311 -6.77555 24.198 11.625)" gradientUnits="userSpaceOnUse"><stop offset=".312" class="xprz9fb8l"/><stop offset="1" class="udkby11pg"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:map-of-japan" /></template>
<style>
.d5gxk6bzj {
  stop-color: var(--svg-color--56b895, #56B895);
}

.f_u2nyu6r {
  fill: var(--svg-color--53ae90, #53AE90);
  d: path("M19.01 15.3c0 .39.32.71.71.71c.19 0 .37-.07.5-.21l.59-.59c.13-.13.21-.31.21-.5c0-.39-.32-.71-.71-.71c-.19 0-.37.07-.5.21l-.59.59c-.14.13-.21.31-.21.5");
}

.ft5dv1b6b {
  fill: none;
}

.hu3k27bzb {
  stop-color: var(--svg-color--5cdc9c, #5CDC9C);
}

.k4qlbz9tl {
  stop-color: var(--svg-color--53b18f, #53B18F);
}

.o6vkxo51a {
  stop-color: var(--svg-color--55b593, #55B593);
}

.omyjt1b7q {
  d: path("M22.01 9h.53c.28 0 .5-.22.5-.5s.22-.5.5-.5h1.26c.13 0 .26.05.35.15l.68.68c.11.11.26.16.41.14l.47-.05c.16-.02.3-.11.38-.26l.77-1.4c.09-.16.26-.26.44-.26h1.2c.28 0 .5-.22.5-.5V5.21a.47.47 0 0 0-.15-.35l-.71-.71a.5.5 0 0 0-.35-.15h-1.63c-.74 0-1.45-.29-1.98-.82l-1.04-1.04a.5.5 0 0 0-.35-.15h-1.36c-.28 0-.5.22-.5.5v1c0 .28.22.5.5.5h.07c.28 0 .5.22.5.5v1c0 .28-.22.5-.5.5h-.1c-.78 0-1.4.63-1.4 1.4v.59c.01.57.46 1.02 1.01 1.02");
}

.p65z65b6q {
  stop-color: var(--svg-color--53b491, #53B491);
}

.reu5_10ar {
  d: path("M13.01 25.59a.58.58 0 0 0-.58-.58h-2.28c-.09 0-.18.02-.26.06l-1.09.55c-.48.24-.79.73-.79 1.27v.54c0 .32.26.58.58.58h.84c.32 0 .58-.26.58-.58c0-.25.16-.47.4-.55l2.21-.74c.23-.08.39-.3.39-.55");
}

.s2al21b8l {
  d: path("M3 27.51v2c0 .28.22.5.5.5h.43c1.22 0 2.28-.83 2.57-2.01l.43-1.72a.5.5 0 0 0-.13-.47l-1.65-1.65a.5.5 0 0 0-.35-.15H3.32c-.19 0-.36.11-.45.28l-.81 1.62c-.03.07-.05.15-.05.22v.38c0 .28.22.5.5.5c.27 0 .49.22.49.5");
}

.syuxsmbeu {
  d: path("m7.13 22.31l-.57.85c-.24.36.02.85.45.85h6.37c.34 0 .61.27.61.61v.02c0 .76.61 1.37 1.37 1.37h.13c.83 0 1.5-.67 1.5-1.5c0-.29.21-.54.49-.6l3.56-.71c.62-.12 1.19-.43 1.63-.88l.14-.14c.12-.12.27-.18.44-.18h.02c.46 0 .91-.18 1.24-.51c.31-.31.49-.73.49-1.17v-4.21c0-.07.01-.13.03-.19l.87-2.62c.06-.18.03-.38-.07-.53l-1.47-2.2a.69.69 0 0 0-.93-.21l-.96.59c-.29.18-.47.5-.47.84v3.49c0 .34-.27.61-.61.61c-.24 0-.45.14-.55.35l-.67 1.42a.62.62 0 0 1-.55.35c-.34 0-.61-.27-.61-.61v-.07c0-.34-.27-.61-.61-.61h-.78c-.34 0-.61.27-.61.61v.58c0 .13-.04.25-.11.35l-.42.59A5.1 5.1 0 0 1 12.32 21H9.58c-.99.01-1.9.5-2.45 1.31");
}

.udkby11pg {
  stop-color: var(--svg-color--57bf96, #57BF96);
}

.xprz9fb8l {
  stop-color: var(--svg-color--5bd49a, #5BD49A);
}

.zqi7brybz {
  stop-color: var(--svg-color--5fe49f, #5FE49F);
}

</style>
