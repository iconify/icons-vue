<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg1yxfb0n.css';
import '../../css/s/stheyzbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eg1yxfb0n"/><path class="stheyzbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:version-major" /></template>
