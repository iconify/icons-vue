<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuahm6pfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuahm6pfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ticket-filled" /></template>
