<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er16xtb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="er16xtb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paintbrush-1" /></template>
