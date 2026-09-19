<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e00l-by_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e00l-by_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:twitter-small" /></template>
