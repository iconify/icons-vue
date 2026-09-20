<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5456z5rt.css';
import '../../css/v/v5gc3bcuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5456z5rt"/><path class="v5gc3bcuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:photo-album-line" /></template>
