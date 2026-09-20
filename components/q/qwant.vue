<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tafes-bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tafes-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qwant" /></template>
