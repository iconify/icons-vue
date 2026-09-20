<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dagcc8buf.css';
import '../../css/n/ny7q1b0qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dagcc8buf"/><path class="ny7q1b0qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:target-user" /></template>
