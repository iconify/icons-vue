<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-9x3oqjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":496};
const content = `<path class="k-9x3oqjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sort-desc" /></template>
