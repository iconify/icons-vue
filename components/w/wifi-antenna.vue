<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1sj30ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j1sj30ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-antenna" /></template>
