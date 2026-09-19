<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwq1tebbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwq1tebbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:uno" /></template>
