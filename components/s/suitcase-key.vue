<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgm_574jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vgm_574jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:suitcase-key" /></template>
