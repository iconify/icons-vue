<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu_gduejx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu_gduejx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:yen-solid" /></template>
