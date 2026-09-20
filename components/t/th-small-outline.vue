<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0zhx4z6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0zhx4z6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:th-small-outline" /></template>
