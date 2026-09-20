<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhztmo4mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yhztmo4mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pennsylvania-with-capital-star" /></template>
