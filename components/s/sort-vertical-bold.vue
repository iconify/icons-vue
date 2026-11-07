<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0nj5essx.css';
import '../../css/t/tl8qmubzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0nj5essx"/><path class="tl8qmubzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-vertical-bold" /></template>
