<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd3i1hf5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd3i1hf5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:time-duration-off" /></template>
