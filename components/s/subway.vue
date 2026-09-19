<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e76d37bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e76d37bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:subway" /></template>
