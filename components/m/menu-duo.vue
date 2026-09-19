<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdc5flbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdc5flbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:menu-duo" /></template>
