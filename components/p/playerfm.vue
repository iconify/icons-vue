<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5t5qvb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g5t5qvb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:playerfm" /></template>
