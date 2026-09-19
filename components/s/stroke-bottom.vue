<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfbh3cbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfbh3cbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stroke-bottom" /></template>
