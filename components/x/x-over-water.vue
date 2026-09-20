<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z62gofbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z62gofbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:x-over-water" /></template>
