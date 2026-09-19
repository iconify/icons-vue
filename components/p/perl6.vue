<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gey7z4w5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gey7z4w5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:perl6" /></template>
