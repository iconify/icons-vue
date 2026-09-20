<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-5cd9qq.css';
import '../../css/t/tjtae605g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-5cd9qq"/><path clip-rule="evenodd" class="tjtae605g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:scroll-down-2" /></template>
