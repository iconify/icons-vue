<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yipit4bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yipit4bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:square-full" /></template>
