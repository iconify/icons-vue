<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs3w-gm0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs3w-gm0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-6-fill-round" /></template>
