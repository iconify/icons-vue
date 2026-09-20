<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddd5e-bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddd5e-bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pentagon-remix" /></template>
