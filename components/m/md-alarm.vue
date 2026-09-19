<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2w7lwbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n2w7lwbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-alarm" /></template>
