<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr1gj811x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qr1gj811x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:umami-light" /></template>
