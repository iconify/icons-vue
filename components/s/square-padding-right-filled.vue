<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izzk8ehcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izzk8ehcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-padding-right-filled" /></template>
