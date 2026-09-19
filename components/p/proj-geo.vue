<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-keo3gqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="q-keo3gqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:proj-geo" /></template>
