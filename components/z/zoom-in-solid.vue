<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1orefbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1orefbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zoom-in-solid" /></template>
