<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om1xn7ejk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="om1xn7ejk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:robinson-dark" /></template>
