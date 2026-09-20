<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2v5bx4nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t2v5bx4nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:propane-tank" /></template>
