<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w45cde5tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w45cde5tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-e-filled" /></template>
