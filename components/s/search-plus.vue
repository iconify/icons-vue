<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uowjoqehi.css';
import '../../css/s/se-m8-fzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uowjoqehi"/><path class="se-m8-fzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-plus" /></template>
