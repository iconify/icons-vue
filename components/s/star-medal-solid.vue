<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9diafb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c9diafb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:star-medal-solid" /></template>
