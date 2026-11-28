<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7op_oidd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7op_oidd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rocking-chair-solid" /></template>
