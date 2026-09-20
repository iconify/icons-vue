<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whl_7lbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whl_7lbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spoolman-dark" /></template>
