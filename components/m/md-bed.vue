<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc46ed-rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc46ed-rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-bed" /></template>
