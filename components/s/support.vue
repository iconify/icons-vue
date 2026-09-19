<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knxfsw6ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="knxfsw6ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:support" /></template>
