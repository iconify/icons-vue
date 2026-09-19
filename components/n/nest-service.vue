<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkbd6vbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lkbd6vbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nest-service" /></template>
