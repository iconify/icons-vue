<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3ar17e1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ar17e1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:search-solid" /></template>
