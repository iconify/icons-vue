<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apr2eo5qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apr2eo5qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-round" /></template>
