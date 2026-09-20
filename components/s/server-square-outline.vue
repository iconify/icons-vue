<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-v3g4bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-v3g4bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-square-outline" /></template>
