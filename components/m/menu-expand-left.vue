<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypeyqq57o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypeyqq57o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:menu-expand-left" /></template>
