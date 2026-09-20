<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rizejjk-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rizejjk-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:math-tangent" /></template>
