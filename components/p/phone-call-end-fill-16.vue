<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od67l8b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="od67l8b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-end-fill-16" /></template>
