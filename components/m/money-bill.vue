<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw78bx2nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qw78bx2nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:money-bill" /></template>
