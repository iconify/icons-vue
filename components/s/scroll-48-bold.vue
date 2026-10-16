<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhhvqwbng.css';
import '../../css/e/era03mble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhhvqwbng"/><path class="era03mble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scroll-48-bold" /></template>
