<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3mmdyl1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r3mmdyl1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:package-library" /></template>
