<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu9cxub5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu9cxub5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-vacuum-variant" /></template>
