<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpxmj1fbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fpxmj1fbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visernic-dark" /></template>
