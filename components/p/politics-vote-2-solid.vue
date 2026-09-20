<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_uydcygs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_uydcygs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:politics-vote-2-solid" /></template>
