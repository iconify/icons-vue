<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5do6h3hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t5do6h3hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:patreon" /></template>
