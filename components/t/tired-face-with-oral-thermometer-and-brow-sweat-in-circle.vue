<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ndmlpoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p7ndmlpoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-oral-thermometer-and-brow-sweat-in-circle" /></template>
