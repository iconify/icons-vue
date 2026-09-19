<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaxkd8bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uaxkd8bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:zoom-in" /></template>
