<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euz3adbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="euz3adbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:take-off-remix" /></template>
