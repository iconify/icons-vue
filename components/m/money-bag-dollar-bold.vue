<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3ay99b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ay99b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:money-bag-dollar-bold" /></template>
