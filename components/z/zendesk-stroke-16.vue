<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvk-mpx8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vvk-mpx8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:zendesk-stroke-16" /></template>
