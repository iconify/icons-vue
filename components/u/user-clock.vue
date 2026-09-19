<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu_mcwbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="iu_mcwbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:user-clock" /></template>
