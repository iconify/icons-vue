<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2m5s5bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="s2m5s5bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:paragraph-start" /></template>
