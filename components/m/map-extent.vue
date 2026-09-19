<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7l3pbb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="j7l3pbb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-extent" /></template>
