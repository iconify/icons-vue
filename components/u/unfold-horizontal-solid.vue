<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvkz2fbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvkz2fbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:unfold-horizontal-solid" /></template>
