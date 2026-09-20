<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5xvhpb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5xvhpb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-previous" /></template>
