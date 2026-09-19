<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxhi8gm6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxhi8gm6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:three" /></template>
