<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwt369onn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kwt369onn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:recycle-1-solid" /></template>
