<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k845eb9af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k845eb9af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-videocam" /></template>
