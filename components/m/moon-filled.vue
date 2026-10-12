<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_9ogobgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_9ogobgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:moon-filled" /></template>
