<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfg36uboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="sfg36uboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pacifier" /></template>
