<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbska5vsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dbska5vsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:trending-content-remix" /></template>
