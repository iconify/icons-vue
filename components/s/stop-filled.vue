<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydyvfu86y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ydyvfu86y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:stop-filled" /></template>
