<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj13y4bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj13y4bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:progress-50-fill" /></template>
