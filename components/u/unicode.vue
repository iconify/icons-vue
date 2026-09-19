<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s73i_9bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s73i_9bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:unicode" /></template>
