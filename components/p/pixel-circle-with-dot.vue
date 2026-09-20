<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7-8-1t_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l7-8-1t_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-circle-with-dot" /></template>
