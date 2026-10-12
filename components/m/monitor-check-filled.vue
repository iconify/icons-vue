<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8eoc3-8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8eoc3-8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-check-filled" /></template>
