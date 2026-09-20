<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc77nee5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jc77nee5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-tap-with-handle-and-droplet" /></template>
