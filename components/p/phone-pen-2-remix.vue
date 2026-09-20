<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v473bfbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v473bfbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-pen-2-remix" /></template>
