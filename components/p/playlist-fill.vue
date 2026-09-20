<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5tb48bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5tb48bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:playlist-fill" /></template>
