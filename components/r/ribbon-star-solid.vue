<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp74bbcgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp74bbcgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ribbon-star-solid" /></template>
