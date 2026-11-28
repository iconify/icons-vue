<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm5fw8qnf.css';
import '../../css/s/sd92k-bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm5fw8qnf secondary"/><path class="primary sd92k-bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-8-duo" /></template>
