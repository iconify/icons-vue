<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcn_8mzlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcn_8mzlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:potted-plant-round" /></template>
