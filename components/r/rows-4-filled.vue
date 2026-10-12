<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw96_ebrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw96_ebrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rows-4-filled" /></template>
