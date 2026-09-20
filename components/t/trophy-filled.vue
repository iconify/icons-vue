<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sewx3-8el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sewx3-8el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trophy-filled" /></template>
