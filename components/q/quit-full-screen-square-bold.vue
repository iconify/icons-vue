<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgomtdbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgomtdbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-square-bold" /></template>
