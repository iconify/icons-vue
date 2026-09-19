<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whft5_bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="whft5_bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:tumblr" /></template>
