<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjldgvq9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gjldgvq9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:slide-and-droplet" /></template>
