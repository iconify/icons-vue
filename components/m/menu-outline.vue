<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn9bmzbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn9bmzbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:menu-outline" /></template>
