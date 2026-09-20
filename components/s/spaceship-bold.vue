<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrnak2bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrnak2bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:spaceship-bold" /></template>
