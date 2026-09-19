<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci-09np2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci-09np2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:sun" /></template>
