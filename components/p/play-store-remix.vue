<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbese6xie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbese6xie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:play-store-remix" /></template>
