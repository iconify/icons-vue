<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu9tfg_yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yu9tfg_yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-rke-light" /></template>
