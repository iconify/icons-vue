<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfga9qgse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bfga9qgse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-compress-vertical" /></template>
