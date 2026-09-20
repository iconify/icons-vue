<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwecivbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwecivbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pushpin-2-line" /></template>
