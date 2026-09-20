<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg2l0flxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg2l0flxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:threadless" /></template>
