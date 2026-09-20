<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwjty5okl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwjty5okl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shirt-duotone" /></template>
