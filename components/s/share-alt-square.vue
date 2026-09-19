<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v15o35bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="v15o35bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:share-alt-square" /></template>
