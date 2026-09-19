<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjkzw0bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="qjkzw0bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-basket-add" /></template>
