<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-8t4ybdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-8t4ybdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ticket-filled" /></template>
