<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj17dhbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pj17dhbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ordnance-survey-benchmark" /></template>
