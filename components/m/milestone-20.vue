<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnw4jqz8j.css';
import '../../css/u/uwp-39bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gnw4jqz8j"/><path class="uwp-39bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milestone-20" /></template>
