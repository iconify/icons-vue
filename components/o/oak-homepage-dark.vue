<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffqzsgefn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffqzsgefn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oak-homepage-dark" /></template>
