<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/greuehjne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="greuehjne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:server-filled" /></template>
