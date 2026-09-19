<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch4s936vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch4s936vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:separator-horizontal" /></template>
