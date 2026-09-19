<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bic_6imzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="bic_6imzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-basket-remove" /></template>
