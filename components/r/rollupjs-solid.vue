<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_avgdczx.css';
import '../../css/k/kc709bcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l_avgdczx"/><path class="kc709bcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rollupjs-solid" /></template>
