<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eugcecc6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eugcecc6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ring-remix" /></template>
