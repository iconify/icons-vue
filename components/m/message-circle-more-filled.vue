<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqq7qyo5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iqq7qyo5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-more-filled" /></template>
