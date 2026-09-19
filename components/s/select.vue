<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut86ghblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":44,"height":24};
const content = `<path clip-rule="evenodd" class="ut86ghblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:select" /></template>
