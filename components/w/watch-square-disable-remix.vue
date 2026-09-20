<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_p0phbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_p0phbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:watch-square-disable-remix" /></template>
