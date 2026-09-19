<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9bhgvbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n9bhgvbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pug" /></template>
