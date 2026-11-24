<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uopljoblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uopljoblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paw-print-filled" /></template>
