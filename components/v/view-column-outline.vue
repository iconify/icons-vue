<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft8ybjbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ft8ybjbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:view-column-outline" /></template>
