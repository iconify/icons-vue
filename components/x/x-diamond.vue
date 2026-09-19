<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scjxik53c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="scjxik53c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:x-diamond" /></template>
