<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hguwsyb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hguwsyb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:whatsapp-round" /></template>
