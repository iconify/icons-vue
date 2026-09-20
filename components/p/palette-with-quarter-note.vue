<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyc6aqbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cyc6aqbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:palette-with-quarter-note" /></template>
