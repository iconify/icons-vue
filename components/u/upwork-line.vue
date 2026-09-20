<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjm_bibby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjm_bibby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upwork-line" /></template>
