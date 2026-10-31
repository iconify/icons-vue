<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixp0i4b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixp0i4b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-fill-round" /></template>
