<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7pdt9bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7pdt9bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netonnet-light" /></template>
