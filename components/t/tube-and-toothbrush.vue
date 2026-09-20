<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpds9sb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fpds9sb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tube-and-toothbrush" /></template>
