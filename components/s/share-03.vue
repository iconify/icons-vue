<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8y-w-skm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8y-w-skm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:share-03" /></template>
