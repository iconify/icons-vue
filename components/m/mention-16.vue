<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_67n5afz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w_67n5afz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mention-16" /></template>
