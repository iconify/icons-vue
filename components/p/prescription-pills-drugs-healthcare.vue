<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyalztbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wyalztbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:prescription-pills-drugs-healthcare" /></template>
