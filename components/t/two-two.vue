<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz37df3-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mz37df3-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:two-two" /></template>
