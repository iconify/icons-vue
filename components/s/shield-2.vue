<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll5w1cbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ll5w1cbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shield-2" /></template>
