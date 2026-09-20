<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur6emhwip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur6emhwip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stack-2" /></template>
