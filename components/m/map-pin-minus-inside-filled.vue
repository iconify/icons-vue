<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzgrr6crx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzgrr6crx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-minus-inside-filled" /></template>
