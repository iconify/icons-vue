<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2i0_9x9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2i0_9x9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:zap" /></template>
