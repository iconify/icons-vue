<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr0v3sgyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qr0v3sgyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spoolman-light" /></template>
