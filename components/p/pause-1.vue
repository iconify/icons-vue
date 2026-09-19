<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyofm5_zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyofm5_zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:pause-1" /></template>
