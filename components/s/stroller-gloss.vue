<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5x_c4b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5x_c4b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stroller-gloss" /></template>
