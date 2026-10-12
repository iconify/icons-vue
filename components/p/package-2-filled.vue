<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7esz6bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7esz6bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-2-filled" /></template>
