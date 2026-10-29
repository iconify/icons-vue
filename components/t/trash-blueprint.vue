<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/a-n3ew6zo.css';
import '../../css/a/acrplfeco.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/f/fnqqe5b5e.css';
import '../../css/c/c7xnwmbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="a-n3ew6zo wm-deco"/><path class="acrplfeco wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="fnqqe5b5e wm-k"/><path class="c7xnwmbpp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trash-blueprint" /></template>
