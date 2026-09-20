<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aco_-tbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="aco_-tbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:updown" /></template>
