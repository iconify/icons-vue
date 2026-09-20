<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8xtb3bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8xtb3bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-circle-bold" /></template>
