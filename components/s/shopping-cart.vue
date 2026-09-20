<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_-sezehz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_-sezehz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shopping-cart" /></template>
