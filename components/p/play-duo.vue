<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1i6nebwi.css';
import '../../css/n/nsykuxbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1i6nebwi secondary"/><path class="nsykuxbye primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-duo" /></template>
