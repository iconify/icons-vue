<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgof5_bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgof5_bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:search-alt" /></template>
