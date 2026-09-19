<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt73z4b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mt73z4b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:window" /></template>
