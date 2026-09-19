<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhxn8lbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhxn8lbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:share-computer" /></template>
