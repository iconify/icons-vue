<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d81fbrxtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d81fbrxtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-j-filled" /></template>
