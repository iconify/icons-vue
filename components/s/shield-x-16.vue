<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf80xcb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf80xcb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-x-16" /></template>
