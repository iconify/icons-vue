<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfksmbcop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfksmbcop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-horizontal-thin" /></template>
