<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itclvu5is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itclvu5is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:typescript-alt" /></template>
