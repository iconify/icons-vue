<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ael58jbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ael58jbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-intersect" /></template>
