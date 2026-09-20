<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xscml5ysl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xscml5ysl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-basket-2-remix" /></template>
