<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chw7yu-vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chw7yu-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:women-outline" /></template>
