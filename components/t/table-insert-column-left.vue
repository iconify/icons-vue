<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f51zekmzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f51zekmzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:table-insert-column-left" /></template>
