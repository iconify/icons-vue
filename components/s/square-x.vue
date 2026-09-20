<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr-j4s5gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr-j4s5gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-x" /></template>
