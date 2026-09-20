<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5udqqn5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5udqqn5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tram-side" /></template>
