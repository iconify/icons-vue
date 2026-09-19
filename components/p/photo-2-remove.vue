<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5__1z18o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g5__1z18o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:photo-2-remove" /></template>
