<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq__i_bat.css';
import '../../css/l/lpad86zwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lq__i_bat"/><path class="lpad86zwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:touch-1-filled" /></template>
