<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgnzrg3dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnzrg3dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:window-open-solid" /></template>
