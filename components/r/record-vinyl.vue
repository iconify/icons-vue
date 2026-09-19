<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fygf62kln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fygf62kln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:record-vinyl" /></template>
