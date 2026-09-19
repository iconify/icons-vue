<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px047eycd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="px047eycd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:walking" /></template>
