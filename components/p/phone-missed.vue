<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ioq2yrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ioq2yrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-missed" /></template>
