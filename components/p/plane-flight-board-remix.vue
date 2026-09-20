<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb-bf3b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb-bf3b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:plane-flight-board-remix" /></template>
