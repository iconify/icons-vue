<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr7ok7mjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="dr7ok7mjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:text-solid" /></template>
