<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6sim5rjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6sim5rjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:signal-2" /></template>
