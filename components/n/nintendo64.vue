<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thembzy5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="thembzy5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nintendo64" /></template>
