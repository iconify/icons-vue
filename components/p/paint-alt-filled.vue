<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygigg_h9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygigg_h9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paint-alt-filled" /></template>
