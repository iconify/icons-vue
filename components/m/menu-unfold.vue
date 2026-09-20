<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh1hauwkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vh1hauwkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:menu-unfold" /></template>
