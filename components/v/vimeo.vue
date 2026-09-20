<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csjmgi5ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csjmgi5ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:vimeo" /></template>
