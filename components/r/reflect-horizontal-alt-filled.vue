<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya80we8aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya80we8aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reflect-horizontal-alt-filled" /></template>
