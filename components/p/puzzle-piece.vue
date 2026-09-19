<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-4nfhedr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-4nfhedr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:puzzle-piece" /></template>
