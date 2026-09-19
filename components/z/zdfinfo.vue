<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymn7yrb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymn7yrb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zdfinfo" /></template>
