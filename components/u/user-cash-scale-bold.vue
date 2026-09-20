<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi7_4fbxw.css';
import '../../css/v/v4344lbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi7_4fbxw"/><path class="v4344lbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:user-cash-scale-bold" /></template>
