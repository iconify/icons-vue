<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy0uqnbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0uqnbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:play" /></template>
