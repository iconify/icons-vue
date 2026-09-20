<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb-mk4b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb-mk4b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peanut-dark" /></template>
