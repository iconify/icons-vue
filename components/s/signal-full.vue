<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exill43ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="exill43ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:signal-full" /></template>
