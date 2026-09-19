<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmzpx5bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmzpx5bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:umbrella-outline" /></template>
