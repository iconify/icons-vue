<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3zlp8h8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3zlp8h8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:signature" /></template>
