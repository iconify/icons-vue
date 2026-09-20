<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv0lq0-ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tv0lq0-ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:table" /></template>
