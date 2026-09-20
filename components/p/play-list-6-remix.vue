<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifuj_jsse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ifuj_jsse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:play-list-6-remix" /></template>
