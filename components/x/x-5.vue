<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2-c3ot9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x2-c3ot9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:x-5" /></template>
