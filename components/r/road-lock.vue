<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2sxe262x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="e2sxe262x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:road-lock" /></template>
