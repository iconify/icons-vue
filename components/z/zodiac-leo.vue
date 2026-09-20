<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u72a_0bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u72a_0bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zodiac-leo" /></template>
