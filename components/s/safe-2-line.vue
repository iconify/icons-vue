<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdsrg8boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdsrg8boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:safe-2-line" /></template>
