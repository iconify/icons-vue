<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic7rc9bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic7rc9bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shrink-right" /></template>
