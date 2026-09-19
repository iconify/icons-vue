<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7uv1b9z.css';
import '../../css/e/eqckd4mok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn7uv1b9z"/><path class="eqckd4mok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:thumbsup" /></template>
