<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsy1unb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsy1unb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:stroopwafel" /></template>
