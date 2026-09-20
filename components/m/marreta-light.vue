<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdpi_bbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdpi_bbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marreta-light" /></template>
