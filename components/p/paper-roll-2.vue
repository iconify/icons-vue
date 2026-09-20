<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpsaa-b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpsaa-b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:paper-roll-2" /></template>
