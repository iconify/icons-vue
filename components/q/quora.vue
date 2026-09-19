<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnl4fvoaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rnl4fvoaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:quora" /></template>
