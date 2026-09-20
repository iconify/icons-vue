<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct7zfpb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct7zfpb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tubi" /></template>
