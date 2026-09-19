<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6ew29b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m6ew29b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-pause-stroke-16" /></template>
