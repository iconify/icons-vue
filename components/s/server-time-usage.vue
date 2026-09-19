<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj9vjz3-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jj9vjz3-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:server-time-usage" /></template>
