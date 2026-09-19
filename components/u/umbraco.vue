<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l__fx2hzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l__fx2hzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:umbraco" /></template>
