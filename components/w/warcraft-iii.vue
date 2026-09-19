<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrwpp37dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrwpp37dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:warcraft-iii" /></template>
