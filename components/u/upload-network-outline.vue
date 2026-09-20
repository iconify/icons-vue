<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar7hmtfxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7hmtfxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:upload-network-outline" /></template>
