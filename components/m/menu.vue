<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v106kq0eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v106kq0eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:menu" /></template>
