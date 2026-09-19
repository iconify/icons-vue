<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usj0p_4lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="usj0p_4lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:unlink" /></template>
