<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9v1q2zst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m9v1q2zst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mall-remix" /></template>
