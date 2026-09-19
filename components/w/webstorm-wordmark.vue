<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfb62obzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jfb62obzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:webstorm-wordmark" /></template>
