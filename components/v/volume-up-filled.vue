<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j35eaocdf.css';
import '../../css/x/x0gu7cb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j35eaocdf"/><path class="x0gu7cb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-up-filled" /></template>
