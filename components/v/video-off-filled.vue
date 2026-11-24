<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lba1z4b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lba1z4b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:video-off-filled" /></template>
