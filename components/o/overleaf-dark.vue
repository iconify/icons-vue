<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9g-gmbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9g-gmbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:overleaf-dark" /></template>
