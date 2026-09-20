<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gor4ayb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gor4ayb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:signal-full-remix" /></template>
