<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqa938w4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oqa938w4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:progress-full" /></template>
