<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2d6l49my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2d6l49my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-qr-code-filled" /></template>
