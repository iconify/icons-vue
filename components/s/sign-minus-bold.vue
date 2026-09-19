<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyc5hev-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyc5hev-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-bold" /></template>
