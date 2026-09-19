<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3o6zp8oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3o6zp8oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-ropelight" /></template>
