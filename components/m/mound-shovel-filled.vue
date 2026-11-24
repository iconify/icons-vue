<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hens0-_pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hens0-_pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mound-shovel-filled" /></template>
