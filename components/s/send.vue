<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqqq5obas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqqq5obas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:send" /></template>
