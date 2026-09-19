<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmsje_bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="nmsje_bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:stack-overflow" /></template>
