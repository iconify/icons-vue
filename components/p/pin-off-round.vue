<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayh0pmhui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayh0pmhui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-off-round" /></template>
