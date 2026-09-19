<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlla0b0fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlla0b0fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-fast" /></template>
