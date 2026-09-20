<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe5r8nmyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5r8nmyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:octagon" /></template>
