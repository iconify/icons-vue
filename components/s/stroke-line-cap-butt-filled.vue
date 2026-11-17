<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef80_t4pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ef80_t4pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-line-cap-butt-filled" /></template>
