<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9as19z5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v9as19z5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shopping-basket-2-solid" /></template>
