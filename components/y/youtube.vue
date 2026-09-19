<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxvtyc1ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":609,"height":768};
const content = `<path class="cxvtyc1ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:youtube" /></template>
