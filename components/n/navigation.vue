<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4fj2ibaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l4fj2ibaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:navigation" /></template>
