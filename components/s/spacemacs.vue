<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q79be8dyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q79be8dyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:spacemacs" /></template>
