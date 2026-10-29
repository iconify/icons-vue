<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/m6u5yxbxj.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/b/bhiae9bke.css';
import '../../css/f/fd6pd66bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="m6u5yxbxj wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="bhiae9bke wm-k"/><path class="fd6pd66bu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:notepad-text-blueprint" /></template>
