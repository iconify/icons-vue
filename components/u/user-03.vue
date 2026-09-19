<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6y2bzbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6y2bzbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-03" /></template>
