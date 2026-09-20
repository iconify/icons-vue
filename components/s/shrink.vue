<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-8q-fo5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8q-fo5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shrink" /></template>
