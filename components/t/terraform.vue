<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkbkcot3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kkbkcot3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:terraform" /></template>
