<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpsanhuer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vpsanhuer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:undo2" /></template>
