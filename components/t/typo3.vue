<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt0xp9boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lt0xp9boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:typo3" /></template>
