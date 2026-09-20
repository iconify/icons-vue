<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sof4l1tbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sof4l1tbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twenty-crm-dark" /></template>
