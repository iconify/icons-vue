<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6sbgrbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="v6sbgrbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:taxi" /></template>
