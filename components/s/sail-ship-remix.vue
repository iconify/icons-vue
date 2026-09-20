<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq8qgzcnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kq8qgzcnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sail-ship-remix" /></template>
