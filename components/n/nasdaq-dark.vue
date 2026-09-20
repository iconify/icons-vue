<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxgzcwb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxgzcwb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasdaq-dark" /></template>
