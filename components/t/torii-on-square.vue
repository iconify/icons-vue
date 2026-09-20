<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb4kiwbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wb4kiwbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:torii-on-square" /></template>
