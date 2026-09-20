<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex74vg5rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex74vg5rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:microsoft-line" /></template>
