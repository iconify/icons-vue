<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6n8k5bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6n8k5bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:underline" /></template>
