<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndc5i5bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":331,"height":512};
const content = `<path class="ndc5i5bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tipe" /></template>
