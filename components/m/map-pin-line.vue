<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5jodh5el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5jodh5el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-line" /></template>
