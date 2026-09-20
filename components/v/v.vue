<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpxc1-b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fpxc1-b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:v" /></template>
