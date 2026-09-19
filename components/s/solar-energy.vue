<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkip69-5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkip69-5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:solar-energy" /></template>
