<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i68vwmyrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i68vwmyrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minus-circle-solid" /></template>
