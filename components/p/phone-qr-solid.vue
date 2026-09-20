<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3wgpabtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s3wgpabtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-qr-solid" /></template>
