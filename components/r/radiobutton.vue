<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp934ebga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sp934ebga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:radiobutton" /></template>
