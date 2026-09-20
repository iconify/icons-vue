<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq98in52p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq98in52p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search" /></template>
