<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3qa7t8dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3qa7t8dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:shopping-bag" /></template>
