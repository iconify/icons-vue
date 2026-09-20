<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u91jgo_1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u91jgo_1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vanilla-cookbook-dark" /></template>
