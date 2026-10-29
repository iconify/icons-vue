<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gc5-p1bnk.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/c/crfhsoutb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gc5-p1bnk wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="crfhsoutb wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-blueprint" /></template>
