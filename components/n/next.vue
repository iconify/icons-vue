<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erid2sbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="erid2sbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:next" /></template>
