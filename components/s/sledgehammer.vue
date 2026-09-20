<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haj8asbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="haj8asbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sledgehammer" /></template>
