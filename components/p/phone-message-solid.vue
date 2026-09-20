<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzyvgf_8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzyvgf_8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-message-solid" /></template>
