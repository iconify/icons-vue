<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9y5vx-ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9y5vx-ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-chevron-right-filled" /></template>
