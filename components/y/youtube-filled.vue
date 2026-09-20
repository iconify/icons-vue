<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9oz41bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9oz41bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:youtube-filled" /></template>
