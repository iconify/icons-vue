<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3667abak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3667abak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:photorec" /></template>
