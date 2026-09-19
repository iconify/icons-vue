<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfd5t0bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfd5t0bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:paper-plane" /></template>
