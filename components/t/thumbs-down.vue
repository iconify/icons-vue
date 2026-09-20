<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq77w7b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="oq77w7b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:thumbs-down" /></template>
