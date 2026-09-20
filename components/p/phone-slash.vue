<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj2sbxhqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj2sbxhqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:phone-slash" /></template>
