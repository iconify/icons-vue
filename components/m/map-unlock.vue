<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owla9ob2z.css';
import '../../css/q/qjd9umv4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="owla9ob2z"/><path class="qjd9umv4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-unlock" /></template>
