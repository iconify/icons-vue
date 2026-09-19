<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcfs-nj7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcfs-nj7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:moving-platform" /></template>
