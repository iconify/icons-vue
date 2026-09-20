<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_d4z1bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_d4z1bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:scb" /></template>
