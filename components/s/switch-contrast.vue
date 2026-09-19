<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arm89gb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arm89gb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:switch-contrast" /></template>
