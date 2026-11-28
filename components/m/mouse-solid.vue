<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-vpkbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8-vpkbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mouse-solid" /></template>
