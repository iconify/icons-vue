<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us2wi3bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="us2wi3bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-right-bold" /></template>
