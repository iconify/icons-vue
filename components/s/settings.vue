<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okput2b5x.css';
import '../../css/n/n4gtcv7gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="okput2b5x"/><path class="n4gtcv7gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:settings" /></template>
