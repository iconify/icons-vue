<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph1k27nch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph1k27nch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-n-filled" /></template>
