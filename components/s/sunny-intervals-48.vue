<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb9i7xbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fb9i7xbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunny-intervals-48" /></template>
