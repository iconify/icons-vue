<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6h2r6bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t6h2r6bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:windmill" /></template>
