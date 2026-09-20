<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfietobyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfietobyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raspberry-pi-light" /></template>
