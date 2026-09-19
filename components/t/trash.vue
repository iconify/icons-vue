<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo9w_hblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":572,"height":717};
const content = `<path class="eo9w_hblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:trash" /></template>
