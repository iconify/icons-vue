<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7xpn6j1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7xpn6j1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:properties" /></template>
