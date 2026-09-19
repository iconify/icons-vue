<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryd9gmy8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ryd9gmy8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:palette-fill-16" /></template>
