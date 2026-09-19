<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/auzsn3b_x.css';
import '../../css/h/hjfomz99y.css';
import '../../css/b/bmzx_ibhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="auzsn3b_x"/><path class="hjfomz99y"/><path class="bmzx_ibhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:scissors" /></template>
