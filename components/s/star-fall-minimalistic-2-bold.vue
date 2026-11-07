<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqhlzqbqh.css';
import '../../css/w/wt-lpqbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqhlzqbqh"/><path clip-rule="evenodd" class="wt-lpqbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-minimalistic-2-bold" /></template>
