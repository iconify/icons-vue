<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4h6a7xri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="i4h6a7xri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:vroundswitch-off" /></template>
