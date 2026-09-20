<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrp7z4j1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrp7z4j1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shipping-box-1-solid" /></template>
