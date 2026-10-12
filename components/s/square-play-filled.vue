<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpve2kbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpve2kbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-play-filled" /></template>
