<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcpkd6bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gcpkd6bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:podium" /></template>
