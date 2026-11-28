<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7icocbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7icocbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wine-heart" /></template>
