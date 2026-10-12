<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1u9hc7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jg1u9hc7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-euro-filled" /></template>
