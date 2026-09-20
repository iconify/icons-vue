<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/v6my9fadk.css';
import '../../css/t/tmdjm3bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(15 6.336 2.19)" class="v6my9fadk"/><rect transform="rotate(15 10.112 8.73)" class="tmdjm3bnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:roblox" /></template>
