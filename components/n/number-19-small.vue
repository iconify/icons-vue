<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmrsz7b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmrsz7b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-19-small" /></template>
