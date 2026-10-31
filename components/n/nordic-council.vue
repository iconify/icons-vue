<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6_r6x8xh.css';
import '../../css/h/hkoftybrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="z6_r6x8xh"/><path class="hkoftybrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:nordic-council" /></template>
