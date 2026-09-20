<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7c27bb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7c27bb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:play-octagon-solid" /></template>
