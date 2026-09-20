<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic988hg8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic988hg8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:strongbox2-filled" /></template>
