<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu1xexb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu1xexb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mountain-solid" /></template>
