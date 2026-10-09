<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_bfm19uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_bfm19uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-20-bold" /></template>
