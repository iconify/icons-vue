<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd5rvwmxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jd5rvwmxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-star-20-bold" /></template>
