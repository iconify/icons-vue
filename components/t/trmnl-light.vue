<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvz532lhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvz532lhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trmnl-light" /></template>
