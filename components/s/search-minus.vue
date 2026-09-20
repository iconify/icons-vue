<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz9yxmbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz9yxmbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:search-minus" /></template>
