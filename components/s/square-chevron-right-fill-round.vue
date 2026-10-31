<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzmn7bbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzmn7bbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-right-fill-round" /></template>
