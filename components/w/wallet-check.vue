<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqb6y59an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqb6y59an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wallet-check" /></template>
