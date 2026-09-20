<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttut_pbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ttut_pbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-top-right" /></template>
