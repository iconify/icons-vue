<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm72pybvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cm72pybvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:textformat-123" /></template>
