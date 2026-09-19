<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i25j6_12l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i25j6_12l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:menu-alt2" /></template>
