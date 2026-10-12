<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duq8n_bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duq8n_bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wine-off-filled" /></template>
