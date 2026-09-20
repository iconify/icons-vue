<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh3iqkbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh3iqkbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:upload" /></template>
