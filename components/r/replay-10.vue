<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4l7e-bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j4l7e-bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:replay-10" /></template>
