<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5nm_b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zy5nm_b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:stop-slash" /></template>
