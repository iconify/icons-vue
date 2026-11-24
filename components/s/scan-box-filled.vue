<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkdj8isek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkdj8isek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-box-filled" /></template>
