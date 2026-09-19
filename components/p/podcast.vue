<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_sovfbpg.css';
import '../../css/e/ebu29qyhz.css';
import '../../css/u/u7krydeao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_sovfbpg"/><path class="ebu29qyhz"/><path class="u7krydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:podcast" /></template>
