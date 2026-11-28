<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt6cflb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6cflb0y primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-bug-duotone" /></template>
