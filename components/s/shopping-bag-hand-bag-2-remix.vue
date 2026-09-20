<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz55z5bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uz55z5bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shopping-bag-hand-bag-2-remix" /></template>
