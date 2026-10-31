<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3b46xbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3b46xbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-minus-round" /></template>
