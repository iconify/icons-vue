<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhkwwjv2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zhkwwjv2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:share-lock-solid" /></template>
