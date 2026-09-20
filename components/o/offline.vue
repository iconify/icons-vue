<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-wdn4b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-wdn4b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:offline" /></template>
