<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydchm0del.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydchm0del"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pause-circle-solid" /></template>
