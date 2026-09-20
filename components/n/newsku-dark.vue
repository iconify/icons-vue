<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywsqo5b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywsqo5b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newsku-dark" /></template>
