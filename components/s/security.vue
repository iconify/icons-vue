<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgfhitvgx.css';
import '../../css/w/wup9lynlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mgfhitvgx"/><path class="wup9lynlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:security" /></template>
