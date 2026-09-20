<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzn1pt78g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzn1pt78g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:th-large-outline" /></template>
