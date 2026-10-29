<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h3k57tbsl.css';
import '../../css/v/v9uc2q8gc.css';
import '../../css/o/olgj5xbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h3k57tbsl"/><path class="v9uc2q8gc wm-a"/><path class="olgj5xbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:search-duo" /></template>
