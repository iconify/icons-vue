<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak2xm7a5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak2xm7a5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:menu-duo" /></template>
