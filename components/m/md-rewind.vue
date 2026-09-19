<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omh4idx2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omh4idx2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-rewind" /></template>
