<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0d4abdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak0d4abdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spade" /></template>
