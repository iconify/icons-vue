<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa6bskkcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="qa6bskkcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:tv" /></template>
