<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9yf9n-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="li9yf9n-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:seal-shape-bold" /></template>
