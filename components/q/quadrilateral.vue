<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5s5r9buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5s5r9buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:quadrilateral" /></template>
