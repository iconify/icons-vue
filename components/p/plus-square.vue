<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae3o_2bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae3o_2bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plus-square" /></template>
