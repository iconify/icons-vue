<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j25csyqbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j25csyqbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:whale" /></template>
