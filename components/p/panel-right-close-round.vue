<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wce1258hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wce1258hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-close-round" /></template>
