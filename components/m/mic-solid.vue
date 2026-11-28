<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aifiwxboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aifiwxboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mic-solid" /></template>
