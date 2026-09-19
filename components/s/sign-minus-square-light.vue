<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqr3tj4qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr3tj4qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-square-light" /></template>
