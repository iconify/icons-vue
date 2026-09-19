<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh9o9hbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh9o9hbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:rewind-left-outline" /></template>
