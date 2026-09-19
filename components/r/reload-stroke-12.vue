<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzj7dl35p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hzj7dl35p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:reload-stroke-12" /></template>
