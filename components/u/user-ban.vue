<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ujc1b7xbx.css';
import '../../css/y/ya6yf3bzu.css';
import '../../css/x/xi5pfu1br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ujc1b7xbx"/><path class="ya6yf3bzu"/><path clip-rule="evenodd" class="xi5pfu1br"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-ban" /></template>
