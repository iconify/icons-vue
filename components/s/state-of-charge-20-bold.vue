<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7wk2b5mb.css';
import '../../css/c/cbu4-sqbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l7wk2b5mb"/><path class="cbu4-sqbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:state-of-charge-20-bold" /></template>
