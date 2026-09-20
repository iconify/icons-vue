<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p13004bfj.css';
import '../../css/m/m79egobtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p13004bfj"/><path class="m79egobtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:uos" /></template>
