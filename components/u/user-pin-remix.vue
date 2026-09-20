<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx7fe6h-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kx7fe6h-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-pin-remix" /></template>
