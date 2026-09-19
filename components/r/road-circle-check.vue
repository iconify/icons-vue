<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em-0n8irn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="em-0n8irn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:road-circle-check" /></template>
