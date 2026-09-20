<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl0v214ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0v214ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:money-bill-stack" /></template>
