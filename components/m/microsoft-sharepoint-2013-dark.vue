<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwkk4acjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hwkk4acjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sharepoint-2013-dark" /></template>
