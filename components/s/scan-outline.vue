<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkewzlbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkewzlbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:scan-outline" /></template>
