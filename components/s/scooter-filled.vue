<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dak59cc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dak59cc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scooter-filled" /></template>
