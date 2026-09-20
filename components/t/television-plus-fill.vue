<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-6yhbclb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-6yhbclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:television-plus-fill" /></template>
