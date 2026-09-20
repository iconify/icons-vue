<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_3mbzwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_3mbzwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-arrow-right-filled" /></template>
