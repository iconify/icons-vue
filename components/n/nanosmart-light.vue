<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogni7k6ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogni7k6ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nanosmart-light" /></template>
