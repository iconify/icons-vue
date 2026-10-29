<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e5-xx9b2v.css';
import '../../css/t/tyv5asbam.css';
import '../../css/n/n8f7ss6vj.css';
import '../../css/v/v-vraybzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e5-xx9b2v"/><path class="tyv5asbam wm-a"/><path class="n8f7ss6vj wm-k"/><path class="v-vraybzh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:octagon-alert-sketch" /></template>
