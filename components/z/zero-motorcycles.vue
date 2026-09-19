<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh24wfbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh24wfbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zero-motorcycles" /></template>
