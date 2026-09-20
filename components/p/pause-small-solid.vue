<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-lbsdbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i-lbsdbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pause-small-solid" /></template>
