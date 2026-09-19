<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr5v5lb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr5v5lb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:terminal-square" /></template>
