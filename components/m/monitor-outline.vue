<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odqjq-dtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="odqjq-dtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:monitor-outline" /></template>
