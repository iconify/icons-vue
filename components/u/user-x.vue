<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtz98abol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtz98abol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-x" /></template>
