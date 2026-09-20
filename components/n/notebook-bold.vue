<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_txabqkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_txabqkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-bold" /></template>
