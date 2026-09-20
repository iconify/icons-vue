<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwu2i75do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwu2i75do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:move-diagonal-one-solid" /></template>
