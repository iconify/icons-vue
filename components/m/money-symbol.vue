<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3webac-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3webac-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:money-symbol" /></template>
