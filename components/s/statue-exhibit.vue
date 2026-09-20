<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr3hgeb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wr3hgeb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:statue-exhibit" /></template>
