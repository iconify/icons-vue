<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiz9_bcjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiz9_bcjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-alt-round" /></template>
