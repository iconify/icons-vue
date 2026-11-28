<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fytioohms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fytioohms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-pause-solid" /></template>
