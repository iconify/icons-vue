<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3oxvbbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="q3oxvbbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wifi4" /></template>
