<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdgy03bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdgy03bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:self-hosted-gateway" /></template>
