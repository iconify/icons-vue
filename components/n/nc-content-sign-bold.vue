<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt5f_tbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jt5f_tbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:nc-content-sign-bold" /></template>
