<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2cmt0rnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2cmt0rnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-minus" /></template>
