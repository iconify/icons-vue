<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqe1hxm4o.css';
import '../../css/s/s7rqtiajo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gqe1hxm4o"/><path class="s7rqtiajo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:windy-strong" /></template>
