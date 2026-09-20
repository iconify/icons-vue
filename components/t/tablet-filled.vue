<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thcb1pb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thcb1pb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tablet-filled" /></template>
