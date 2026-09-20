<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tch5idbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tch5idbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:volume-level-high-remix" /></template>
