<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_826mby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vg_826mby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:volume-off" /></template>
