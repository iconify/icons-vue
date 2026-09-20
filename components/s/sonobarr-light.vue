<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh8b90bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oh8b90bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonobarr-light" /></template>
