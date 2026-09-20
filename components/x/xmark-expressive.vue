<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj7oc-b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj7oc-b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:xmark-expressive" /></template>
