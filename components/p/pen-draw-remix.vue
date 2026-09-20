<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb8hm84kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tb8hm84kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-draw-remix" /></template>
