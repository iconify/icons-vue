<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x04kdffme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x04kdffme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-wifi" /></template>
