<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb4ba92qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb4ba92qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vray-logo-solid" /></template>
