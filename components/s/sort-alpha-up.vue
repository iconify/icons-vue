<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od52gv09l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="od52gv09l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sort-alpha-up" /></template>
