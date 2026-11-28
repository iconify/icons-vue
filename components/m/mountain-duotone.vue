<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxwv_6pot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yxwv_6pot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mountain-duotone" /></template>
