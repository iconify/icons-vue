<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8lai_2yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8lai_2yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-bag-hand-bag-2-remix" /></template>
