<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3_b9ib7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i3_b9ib7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rocket" /></template>
