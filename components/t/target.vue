<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t12n633bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t12n633bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:target" /></template>
