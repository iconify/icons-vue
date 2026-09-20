<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bepzpz4hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bepzpz4hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:typo3" /></template>
