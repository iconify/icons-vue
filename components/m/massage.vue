<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyrk4f12c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qyrk4f12c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:massage" /></template>
