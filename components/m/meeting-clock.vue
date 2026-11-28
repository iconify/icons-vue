<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh1zp8bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh1zp8bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:meeting-clock" /></template>
