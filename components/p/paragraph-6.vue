<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql2ho69vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ql2ho69vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:paragraph-6" /></template>
