<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vefif0bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vefif0bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:swift" /></template>
