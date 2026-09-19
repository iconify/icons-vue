<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0h03dbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0h03dbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shield-checkmark" /></template>
