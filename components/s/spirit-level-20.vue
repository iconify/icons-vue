<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_lk_zxsl.css';
import '../../css/x/xjb0j7b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_lk_zxsl"/><path class="xjb0j7b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spirit-level-20" /></template>
