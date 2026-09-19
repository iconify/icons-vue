<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaj2k9b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iaj2k9b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:microscope" /></template>
