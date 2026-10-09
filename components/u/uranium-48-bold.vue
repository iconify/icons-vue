<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9jey4b7b.css';
import '../../css/y/y5r8golxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l9jey4b7b"/><path class="y5r8golxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:uranium-48-bold" /></template>
