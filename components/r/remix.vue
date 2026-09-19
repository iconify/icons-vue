<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5fsg_rre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m5fsg_rre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:remix" /></template>
