<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwhkk5uxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vwhkk5uxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scratch-map-light" /></template>
