<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmqlccbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qmqlccbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vortex-logo-2-solid" /></template>
