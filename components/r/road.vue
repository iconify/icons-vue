<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re6-2bchy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re6-2bchy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:road" /></template>
