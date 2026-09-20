<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm9egmo0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vm9egmo0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:redo" /></template>
