<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sse3loblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sse3loblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reload-circle" /></template>
