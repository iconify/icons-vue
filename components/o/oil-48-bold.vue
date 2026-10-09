<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpu4n9bbu.css';
import '../../css/r/r5moseb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jpu4n9bbu"/><path class="r5moseb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-48-bold" /></template>
