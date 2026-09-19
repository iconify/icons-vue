<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztfup6bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztfup6bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:receipt-filled" /></template>
