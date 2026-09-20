<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l35ux5oxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l35ux5oxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rumble-strip" /></template>
