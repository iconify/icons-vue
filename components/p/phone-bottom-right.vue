<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp7zg1bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sp7zg1bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-bottom-right" /></template>
