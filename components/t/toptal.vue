<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9-ew6bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m9-ew6bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:toptal" /></template>
