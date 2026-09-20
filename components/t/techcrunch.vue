<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m49-_o60c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m49-_o60c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:techcrunch" /></template>
