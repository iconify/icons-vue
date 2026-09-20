<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg38t_b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eg38t_b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortifyr-light" /></template>
