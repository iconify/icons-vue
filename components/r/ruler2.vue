<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s34lqgbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s34lqgbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler2" /></template>
