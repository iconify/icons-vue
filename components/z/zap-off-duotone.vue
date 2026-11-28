<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elhwibb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elhwibb4u primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zap-off-duotone" /></template>
