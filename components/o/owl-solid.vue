<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blkr1-zec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blkr1-zec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:owl-solid" /></template>
