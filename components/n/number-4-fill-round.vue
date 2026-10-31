<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdn7b7brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdn7b7brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-4-fill-round" /></template>
