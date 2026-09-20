<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt19m1bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt19m1bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-module" /></template>
