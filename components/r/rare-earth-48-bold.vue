<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqg6e7vrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yqg6e7vrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rare-earth-48-bold" /></template>
