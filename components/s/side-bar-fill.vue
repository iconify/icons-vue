<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3gd2abci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3gd2abci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:side-bar-fill" /></template>
