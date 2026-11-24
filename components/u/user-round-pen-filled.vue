<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1567mgil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1567mgil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-pen-filled" /></template>
