<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuab0w5hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fuab0w5hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shopping-basket-add-solid" /></template>
