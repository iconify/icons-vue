<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbr59b2hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbr59b2hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:open-external" /></template>
