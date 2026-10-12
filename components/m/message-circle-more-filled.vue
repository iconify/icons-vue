<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3rvfy7cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3rvfy7cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-more-filled" /></template>
