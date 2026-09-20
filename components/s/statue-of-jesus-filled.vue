<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v44b4xb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v44b4xb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:statue-of-jesus-filled" /></template>
