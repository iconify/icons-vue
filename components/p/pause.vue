<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r69wl1bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="r69wl1bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:pause" /></template>
