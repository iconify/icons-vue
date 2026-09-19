<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p95ko6b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p95ko6b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pear" /></template>
