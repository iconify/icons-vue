<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwpfvq7kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwpfvq7kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sd-card-bold" /></template>
