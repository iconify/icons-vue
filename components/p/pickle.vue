<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ux81thv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":370,"height":512};
const content = `<path class="t8ux81thv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pickle" /></template>
