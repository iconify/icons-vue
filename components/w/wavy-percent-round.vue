<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4ka9jb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ka9jb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-percent-round" /></template>
