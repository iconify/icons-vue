<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9z-xfbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="v9z-xfbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pause-circle" /></template>
