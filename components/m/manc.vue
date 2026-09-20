<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os2j4ybkr.css';
import '../../css/r/r2-u52t_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os2j4ybkr"/><path class="r2-u52t_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:manc" /></template>
