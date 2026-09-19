<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry3pdv7ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ry3pdv7ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ppt" /></template>
