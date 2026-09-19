<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tznma-bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":466,"height":654};
const content = `<path class="tznma-bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:n" /></template>
