<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5274xbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d5274xbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:view-grid-outline" /></template>
