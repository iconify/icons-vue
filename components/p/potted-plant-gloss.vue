<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hze5yvdeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hze5yvdeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:potted-plant-gloss" /></template>
