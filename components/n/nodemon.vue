<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3k3wr-ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i3k3wr-ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nodemon" /></template>
