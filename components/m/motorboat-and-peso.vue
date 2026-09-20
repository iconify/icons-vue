<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbomululg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fbomululg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-peso" /></template>
