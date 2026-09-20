<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz04_nbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz04_nbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-bold" /></template>
