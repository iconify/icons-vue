<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as3krsimg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="as3krsimg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-2-down-sharp-fill" /></template>
