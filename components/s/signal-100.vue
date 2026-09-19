<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s26tlbbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s26tlbbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-100" /></template>
