<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay2yoh18g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ay2yoh18g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:portfolio" /></template>
