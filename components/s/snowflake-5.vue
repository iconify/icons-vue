<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6f5--b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="s6f5--b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake-5" /></template>
