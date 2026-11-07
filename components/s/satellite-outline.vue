<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evbbpm8vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="evbbpm8vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:satellite-outline" /></template>
