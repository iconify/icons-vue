<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie_pn6uis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ie_pn6uis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:rocketchat" /></template>
