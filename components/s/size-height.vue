<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_faeobgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o_faeobgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:size-height" /></template>
