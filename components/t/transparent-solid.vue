<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm73ivbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm73ivbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:transparent-solid" /></template>
