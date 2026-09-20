<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5wv_8bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g5wv_8bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:upload" /></template>
