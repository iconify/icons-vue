<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap74bobrt.css';
import '../../css/s/srw4vobtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap74bobrt"/><path class="srw4vobtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:timer-outline" /></template>
