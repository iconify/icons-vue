<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-alhcbxd.css';
import '../../css/i/ifa3sbbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j-alhcbxd"/><path class="ifa3sbbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-chip-20" /></template>
