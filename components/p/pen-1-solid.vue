<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-of0dk-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h-of0dk-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pen-1-solid" /></template>
