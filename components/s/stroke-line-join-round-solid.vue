<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx967rl8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx967rl8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-round-solid" /></template>
