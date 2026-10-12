<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9_i5epxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9_i5epxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-minus-filled" /></template>
