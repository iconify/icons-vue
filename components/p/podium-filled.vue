<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr3tov-zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr3tov-zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:podium-filled" /></template>
