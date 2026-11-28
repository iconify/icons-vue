<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7530fb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7530fb5z primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:swap-duotone" /></template>
