<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f55313bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f55313bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-pound-sterling-filled" /></template>
