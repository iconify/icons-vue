<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr9ouymmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr9ouymmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:stats" /></template>
