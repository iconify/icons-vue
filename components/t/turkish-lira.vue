<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-xchyb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-xchyb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:turkish-lira" /></template>
