<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygemgcbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1027,"height":1026};
const content = `<path class="ygemgcbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:watch" /></template>
