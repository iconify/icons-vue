<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7kxs01qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7kxs01qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sigma-duo" /></template>
