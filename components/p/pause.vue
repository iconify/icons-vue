<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7m4u7bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7m4u7bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:pause" /></template>
