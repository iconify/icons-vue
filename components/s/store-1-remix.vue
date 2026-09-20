<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw1wyjsjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zw1wyjsjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:store-1-remix" /></template>
