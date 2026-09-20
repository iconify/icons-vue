<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skwevl1-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="skwevl1-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:sos-help-emergency-sign-flat" /></template>
