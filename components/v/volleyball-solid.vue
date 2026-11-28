<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_d_h4bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_d_h4bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:volleyball-solid" /></template>
