<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGzhDeytbm)" class="g61d2kbrc"/><path fill="url(#SVGdKxG6cnC)" clip-rule="evenodd" class="x5gix0yjq"/><path fill="url(#SVGVir85bjI)" clip-rule="evenodd" class="qot_2s-9a"/><defs><linearGradient id="SVGzhDeytbm" x1="6.992" x2="16.941" y1="5.919" y2="17.217" gradientUnits="userSpaceOnUse"><stop class="ebq2mgboy"/><stop offset="1" class="cu8te_b2r"/></linearGradient><linearGradient id="SVGdKxG6cnC" x1="7.207" x2="18.469" y1="5.413" y2="18.12" gradientUnits="userSpaceOnUse"><stop class="nmstq8dsr"/><stop offset=".47" class="l_3ghu9fj"/><stop offset="1" class="prkolbb5i"/></linearGradient><linearGradient id="SVGVir85bjI" x1="7.986" x2="15.652" y1="8.748" y2="15.374" gradientUnits="userSpaceOnUse"><stop class="q_1v5rwdg"/><stop offset="1" class="vgwsibb6s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pkr" /></template>
<style>
.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.ebq2mgboy {
  stop-color: var(--svg-color--fffcf8, #fffcf8);
}

.ft5dv1b6b {
  fill: none;
}

.g61d2kbrc {
  d: path("M12.011 20.622c4.785 0 8.663-3.874 8.663-8.651c0-4.778-3.878-8.652-8.663-8.652c-4.784 0-8.662 3.874-8.662 8.652s3.878 8.65 8.662 8.65");
}

.l_3ghu9fj {
  stop-color: var(--svg-color--e20c7b, #e20c7b);
}

.nmstq8dsr {
  stop-color: var(--svg-color--fb18ad, #fb18ad);
}

.prkolbb5i {
  stop-color: var(--svg-color--1d010d, #1d010d);
}

.q_1v5rwdg {
  stop-color: var(--svg-color--ff14a4, #ff14a4);
}

.qot_2s-9a {
  fill-rule: evenodd;
  d: path("M12.187 4.547c-.006.517-.366 1.777-1.794 3.071L8.93 8.957c-.928.855-1.744 1.603-2.138 1.918h2.475l.09.011c.394.04 1.058.113 1.058.613v.5H5.892l-.073.113c-.197.304-.568.884-.568 1.502c0 .89 1.069 2.886 3.218 2.886c1.715 0 3.065-.917 3.52-1.266c.614.45 2.223 1.266 3.81 1.266c1.985 0 2.952-1.148 2.952-2.498c0-1.085-.529-1.755-.709-1.957c.023.214-.123.742-.9 1.164l.327 1.604h-1.53l-.23-1.424l-.389 1.424h-1.496l.54-2.537h2.396V12h-2.334l.236-1.125h2.599s-2.69-2.278-3.437-3.116c-.743-.827-1.626-1.969-1.643-3.206zm-1.485 6.328L10.472 12h1.552l.18-1.125zm-.816 3.938h1.49l.372-1.367l.456 1.367h1.563l-.607-2.076l.354-.473h-3.16zM12.17 12l.922-1.125h1.502L13.722 12zm-3.347 6.187c.99-.112 2.852-.826 3.178-2.812a3.364 3.364 0 0 0 3.178 2.812zm-2.66-3.375H7.68l.27-1.383h.737c.383-.034 1.181-.225 1.339-.737l.112-.394H6.63z");
}

.vgwsibb6s {
  stop-color: var(--svg-color--1c000c, #1c000c);
}

.x5gix0yjq {
  fill-rule: evenodd;
  d: path("m16.916 4.789l.146-.236a9.05 9.05 0 0 1 2.87 3.166l-.248.124a8.76 8.76 0 0 0-2.768-3.054m3.803 7.729H21a8.95 8.95 0 0 1-1.333 4.218l-.287-.062a8.66 8.66 0 0 0 1.339-4.162zm-4.838 7.295l.13.253a9 9 0 0 1-3.983.934v-.281a8.7 8.7 0 0 0 3.859-.9zm-8.471-.4l-.158.231a9.06 9.06 0 0 1-2.908-2.913l.225-.17a8.8 8.8 0 0 0 2.841 2.853m-4.129-7.526H3a9 9 0 0 1 1.035-4.083l.264.101a8.7 8.7 0 0 0-1.018 3.982M12 3h.062v.281h-.056A8.7 8.7 0 0 0 7.77 4.367l-.113-.253A9 9 0 0 1 12.006 3zm8.449 9A8.443 8.443 0 1 1 6.035 6.024a8.443 8.443 0 0 1 14.414 5.97zm.28 0a8.72 8.72 0 0 1-8.726 8.721a8.726 8.726 0 1 1 8.727-8.727z");
}

</style>
