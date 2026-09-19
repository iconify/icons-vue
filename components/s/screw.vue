<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tutls0qog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tutls0qog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:screw" /></template>
