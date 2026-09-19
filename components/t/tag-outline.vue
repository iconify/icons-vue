<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r8b-6stnd.css';
import '../../css/w/waljwkoqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tag-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="r8b-6stnd"/><path class="waljwkoqj"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:tag-outline" /></template>
