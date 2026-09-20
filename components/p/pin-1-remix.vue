<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly4d_7b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly4d_7b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pin-1-remix" /></template>
