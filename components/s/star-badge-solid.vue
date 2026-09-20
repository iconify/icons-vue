<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8xv4ht1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p8xv4ht1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:star-badge-solid" /></template>
