<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay6-3hbyq.css';
import '../../css/y/ymie1nvqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ay6-3hbyq"/><path class="ymie1nvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-hot" /></template>
