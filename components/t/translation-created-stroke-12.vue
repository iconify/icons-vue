<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7baw6bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i7baw6bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-created-stroke-12" /></template>
