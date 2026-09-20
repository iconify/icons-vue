<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4sh5gbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4sh5gbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:receipt-text" /></template>
