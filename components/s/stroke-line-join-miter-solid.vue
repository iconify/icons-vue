<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux7jf8buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux7jf8buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-miter-solid" /></template>
