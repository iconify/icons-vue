<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2hbdcbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i2hbdcbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:traffic-cushion" /></template>
