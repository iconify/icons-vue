<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeh_gubsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeh_gubsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:phone-check" /></template>
