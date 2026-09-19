<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg1m4vb6k.css';
import '../../css/e/ey_5yvb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wg1m4vb6k"/><path class="ey_5yvb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thunderstorm-scattered" /></template>
