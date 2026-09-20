<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v53uzibxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v53uzibxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:unspash-logo" /></template>
