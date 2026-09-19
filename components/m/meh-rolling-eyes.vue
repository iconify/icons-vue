<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiesivb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="oiesivb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:meh-rolling-eyes" /></template>
