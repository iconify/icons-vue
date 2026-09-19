<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7bclh6ay.css';
import '../../css/e/e9s0ab8fq.css';
import '../../css/y/y8uolzsot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="y7bclh6ay"/><path class="e9s0ab8fq"/><path class="y8uolzsot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:phone-route-alt-r" /></template>
