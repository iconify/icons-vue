<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfyvv4ilo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfyvv4ilo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shipping-box-1-remix" /></template>
