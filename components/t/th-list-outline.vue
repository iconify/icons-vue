<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3x8owb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3x8owb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:th-list-outline" /></template>
