<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8wtggbuj.css';
import '../../css/r/r7cq4bfcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k8wtggbuj"/><path class="r7cq4bfcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:traffic-incident" /></template>
