<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/equ276bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="equ276bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:share-android-16" /></template>
