<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy32ckbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy32ckbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:n64" /></template>
