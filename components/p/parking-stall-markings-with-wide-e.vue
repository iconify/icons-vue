<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri-3uvbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ri-3uvbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:parking-stall-markings-with-wide-e" /></template>
