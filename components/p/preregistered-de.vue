<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol8sgrj7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ol8sgrj7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de" /></template>
