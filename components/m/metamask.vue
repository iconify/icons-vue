<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f1zurkbdm"/><path class="s6m8i7btm"/><path class="i8uaw-biv"/><path class="ur5xp1b5z"/><path class="ipjkzmbby"/><path class="gml77qbda"/><path class="ml6ctvt6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:metamask" /></template>
<style>
.f1zurkbdm {
  fill: var(--svg-color--ff5c16, #ff5c16);
  d: path("m19.821 19.918l-3.877-1.131l-2.924 1.712h-2.04l-2.926-1.712l-3.875 1.13L3 16.02l1.179-4.327L3 8.034L4.179 3.5l6.056 3.544h3.53L19.821 3.5L21 8.034l-1.179 3.658L21 16.02z");
}

.ft5dv1b6b {
  fill: none;
}

.gml77qbda {
  fill: var(--svg-color--c0c4cd, #c0c4cd);
  d: path("M13.02 18.948V20.5h-2.04v-1.552z");
}

.i8uaw-biv {
  fill: var(--svg-color--e34807, #e34807);
  d: path("m8.054 18.787l-3.875 1.13L3 16.022h5.054zm2.452-6.054l.74 4.7l-1.026-2.614l-3.497-.85l1.33-1.236zm5.44 6.054l3.875 1.13L21 16.022h-5.055zm-2.452-6.054l-.74 4.7l1.026-2.614l3.497-.85l-1.331-1.236z");
}

.ipjkzmbby {
  fill: var(--svg-color--661800, #661800);
  d: path("M4.179 3.5L3 8.034l1.179 3.658h2.535l3.28-2.211zm5.594 10.177H8.625l-.626.6l2.222.54zM19.821 3.5L21 8.034l-1.179 3.658h-2.535l-3.28-2.211zm-5.593 10.177h1.15l.626.6l-2.224.541zm-1.209 5.271l.262-.94l-.527-.575h-1.509l-.527.575l.262.94");
}

.ml6ctvt6w {
  fill: var(--svg-color--e7ebf6, #e7ebf6);
  d: path("m8.055 18.785l2.927 1.714v-1.552l-.262-.94zm7.89 0L13.02 20.5v-1.552l.262-.94z");
}

.s6m8i7btm {
  fill: var(--svg-color--ff5c16, #ff5c16);
  d: path("m4.18 3.5l6.055 3.547l-.24 2.434zm3.875 12.52l2.665 1.99l-2.665.777zm2.452-3.286l-.512-3.251l-3.278 2.21h-.002v.001l.01 2.275l1.33-1.235zM19.82 3.5l-6.056 3.547l.24 2.434zm-3.875 12.52l-2.665 1.99l2.665.777zm1.339-4.326v-.002zl-3.279-2.21l-.512 3.25h2.451l1.33 1.236z");
}

.ur5xp1b5z {
  fill: var(--svg-color--ff8d5d, #ff8d5d);
  d: path("m3 16.02l1.179-4.328h2.535l.01 2.276l3.496.85l1.026 2.613l-.527.576l-2.665-1.989H3zm18 0l-1.179-4.328h-2.535l-.01 2.276l-3.496.85l-1.026 2.613l.527.576l2.665-1.989H21zm-7.235-8.976h-3.53l-.24 2.435l1.251 7.95h1.508l1.252-7.95z");
}

</style>
