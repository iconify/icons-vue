<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn-_pbbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn-_pbbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-check-filled" /></template>
