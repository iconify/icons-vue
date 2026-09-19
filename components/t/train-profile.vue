<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emmbnebwc.css';
import '../../css/p/pu8y5lb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="emmbnebwc"/><path class="pu8y5lb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:train-profile" /></template>
