<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc203_r0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc203_r0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-bold" /></template>
