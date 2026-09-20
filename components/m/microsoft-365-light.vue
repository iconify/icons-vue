<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3zy_2bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3zy_2bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-365-light" /></template>
