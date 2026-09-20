<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo7i7561t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo7i7561t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:nose-smell-remix" /></template>
