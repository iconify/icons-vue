<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbnn0jbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="lbnn0jbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:power-input" /></template>
