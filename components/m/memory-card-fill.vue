<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6k831oie.css';
import '../../css/r/rzbbq-lyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6k831oie"/><path class="rzbbq-lyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:memory-card-fill" /></template>
