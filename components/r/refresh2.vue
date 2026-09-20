<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aynmfmbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aynmfmbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh2" /></template>
