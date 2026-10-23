<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip__v4btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip__v4btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square" /></template>
