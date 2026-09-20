<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci_yrdbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci_yrdbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:swimming-pool-stairs-bold" /></template>
