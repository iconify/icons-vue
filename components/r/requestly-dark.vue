<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua3k2blde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ua3k2blde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:requestly-dark" /></template>
