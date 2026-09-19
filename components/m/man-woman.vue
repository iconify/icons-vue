<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc5whdcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gc5whdcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:man-woman" /></template>
