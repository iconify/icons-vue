<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8ei37bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ei37bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:right-angle-triangle-half-filled" /></template>
