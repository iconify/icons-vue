<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3q8zwb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3q8zwb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-plus-16-solid" /></template>
