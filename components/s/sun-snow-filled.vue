<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9auu3bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9auu3bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-snow-filled" /></template>
