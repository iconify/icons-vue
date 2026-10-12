<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pigk12xyw.css';
import '../../css/y/y_8olsb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pigk12xyw"/><path clip-rule="evenodd" class="y_8olsb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:torus-filled" /></template>
