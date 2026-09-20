<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z21hg6baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z21hg6baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:offline" /></template>
