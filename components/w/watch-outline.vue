<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meh6rwzlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meh6rwzlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:watch-outline" /></template>
