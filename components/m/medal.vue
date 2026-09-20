<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys2c0-bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ys2c0-bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:medal" /></template>
