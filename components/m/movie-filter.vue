<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scbj5ebxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scbj5ebxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-filter" /></template>
