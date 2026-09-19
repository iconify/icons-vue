<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlsk20ghj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jlsk20ghj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:twitter-alt-small" /></template>
