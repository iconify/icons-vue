<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh6fk_rhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh6fk_rhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-big" /></template>
