<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rarc7rbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rarc7rbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shopping-bag-check-solid" /></template>
