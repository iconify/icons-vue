<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svlp0_bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svlp0_bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-x-filled" /></template>
