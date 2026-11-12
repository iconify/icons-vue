<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrimst9bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vrimst9bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mini-qr-dark" /></template>
