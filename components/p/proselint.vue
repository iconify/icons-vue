<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5j6imbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5j6imbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:proselint" /></template>
