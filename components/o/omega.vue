<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c91x_7byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c91x_7byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:omega" /></template>
