<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1_i63b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f1_i63b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:screen-1-remix" /></template>
