<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u87sqsbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u87sqsbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:text-shadow-solid" /></template>
