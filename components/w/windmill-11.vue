<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o14i3uhye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="o14i3uhye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:windmill-11" /></template>
