<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb6rkks4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xb6rkks4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:plus-circle-solid" /></template>
